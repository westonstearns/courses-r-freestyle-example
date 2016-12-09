---
title       : Chapter 1 Freestyle
description : Insert the chapter description here
attachments :
  slides_link :

--- type:NormalExercise lang:r xp:100 skills:1 key:8dd0dc50d8
## More movies

A dataset with a selection of movies, `movie_selection`, is available in the workspace.

The packages `dplyr` and `ggplot2` are also pre loaded.

*** =instructions
- Check out the structure of `movie_selection`.

*** =hint
- Use `str()` for the first instruction.

*** =pre_exercise_code
```{r}
# You can also prepare your dataset in a specific way in the pre exercise code

library(MindOnStats)
data(Movies)
movie_selection <- Movies[Movies$Genre %in% c("action", "animated", "comedy"),c("Genre", "Rating", "Run")]

# Clean up the environment
rm(Movies)
```

*** =sample_code
```{r}


```

*** =solution
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki


test_error()

success_msg("Good work! Feel free to continue to explore, there is no wrong answer!")
```
