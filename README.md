# FIFA-Classification

##Context
The datasets provided include the players data for the Career Mode from 
FIFA 15 to FIFA 20 ("fifa20.csv"). The data allows multiple comparison of 
the same players across the last 6 version of the videogame.

Some ideas of possible analysis:

*  Historical comparison between Messi and Ronaldo (what skill attributes changed the most during time - compared to real-life stats);

*  Ideal budget to create a competitive team (at the level of top n teams in Europe) and at which point the budget does not allow to buy significantly better players for the 11-men lineup. An extra is the same comparison with the Potential attribute for the lineup instead of the Overall attribute;

*  Sample analysis of top n% players (e.g. top 5% of the player) to see if some important attributes as Agility or BallControl or Strength have been popular or not acroos the FIFA versions. An example would be seeing that the top 5% players of FIFA 20 are more fast (higher Acceleration and Agility) compared to FIFA 15. The trend of attributes is also an important indication of how some attributes are necessary for players to win games (a version with more top 5% players with high BallControl stats would indicate that the game is more focused on the technique rather than the physicial aspect).

Feel free to use the available dataset the way you prefer and do not hesitate to flag additional files (player images - datasets prior FIFA 15) that could be implemented to the existing CSV files.

Updated dataset available 
[here](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset)

## Content 

*  Every player available in FIFA 15, 16, 17, 18, 19, and also FIFA 20
*  50+ attributes
*  URL of the scraped player
*  Player positions, with the role in the club and in the national team
*  Player attributes with statistics as Attacking, Skills, Defense, Mentality, GK Skills, etc.
*  Player personal data like Nationality, Club, DateOfBirth, Wage, Salary, etc.

##Acknowledgment

Data has been scraped from the publicly available website [sofifa](https://sofifa.com/)

##Notebook .ipynb classification
This notebook was created to provide information about various 
aspects of players using interactive plotly visualizations by exploring it
or we can say EDA(Exploratory Data Analysis). 
It also contains machine learning models which is used 
to classify players based on their position and predict 
the Overall rating of a player based on the features present in the dataset.
