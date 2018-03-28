## Exploratory Visualization with Tableau
The goal of this project is to tell a story supported by useful visualizations generated from Winter Olympic Games dataset using Tableau. The storytelling is that Norway is the best competitor from 1924 to 2006 and used produced four visualizations to support the narrative. Processed data using SQL and python before import it into Tableau for each visualization. 

## Story
Winter Olympic Games was first born in 1924 in Chamonix, France and became a major international sporting event held once every four years for sports practiced on snow and ice. This critical event does not solely exhibit the trace of significant historical events; it also encompasses many athletics’ bittersweet memories and nations honors and integrity. 


The Winter Olympic Games gradually gained its popularity throughout time. As the evidence, the visualization below exhibits that the number participating countries has increased from 10 to 26 from 1924 to 2006. The boosting of competitive tension among participating nations has become more evident than ever. 
Thus, it is natural for us to wonder which country is the best competitor in general at Winter Olympic Games at all time.

![](/Users/Mao/Documents/MyGit/EDA_Tableau/exploratory_visualization_tableau/HeatMapMedalCnt.png)

Before determining the best competitor, it is necessary to fix the measurement used to compare the performance of all participating countries. Although there are many possibilities in constructing the criteria to evaluate the performance of each nation, we will use the total number of earned medals from 1924 to 2006 as our measurement in this report. 
The heat map above displays the five nations acquired the most medals throughout this period. Geographical location and weather condition of these countries serve as advantages in winning more medals at the Winter Olympics Games. As expected, all five nations located in the northern region on the map. Thus, it snows and ices more frequently in these countries than others. Among these five nations, Norway is ranked number one with a total of 279 medals. Although it is attempted to indicate Norway is the best nation at all time, more evidence is needed to support this assumption. 

The visualization below shows the cumulative counts of medals throughout the timeline. Norway which is demonstrated by the red line shows a significantly steady increase and outstanding performance compare to the other four. Even though Russia outperformed Norway from 1984 to 1998, Norway redeemed its reputation of being the best competitor in the following event which was hosted by the United States in 2002. Now, with more proof, it is appropriate to articulate that Norway is the best competitor during this period in Winter Olympic Games.

![](/Users/Mao/Documents/MyGit/EDA_Tableau/exploratory_visualization_tableau/graph3.png)

Scrutinize the data regards to Norway; the following graph proves that athletes participating in cross-country skiing have earned the most significant number of medals throughout history. This result is not surprising for that cross-country skiing has become one of the most popular winter sports in Norway. And many blogs and articles have mentioned that the reason Norwegian athletes performs well in this discipline is that Norway is one of the few nations that invest in this sport.

![](/Users/Mao/Documents/MyGit/EDA_Tableau/exploratory_visualization_tableau/sports.png)

There is no doubt that Norway is the best competitor at Winter Olympic Games from 1924 to 2006 evaluated by pre-defined criteria. Moreover, whether Norway can continue to dominate over other countries or not will be exciting to anticipate.

## Data Process 
### Tutorial 
For more information on data processing for generating visualization, please refer to my tutorial notebook here. 

### Requirement
Below are required packages to performe data process and analysis for this project.
 
* Pandas 
* Psycopg2 - PostgreSQL database adapter for Python

## Install
Here are the instructions to download Tableau Desktop and activate it with the product key for access.

* Click [this link](https://www.tableau.com/tft/activation "Title") link to download the latest version of Tableau Desktop here
* Enter your email address for Business E-mail and the name of your Organization
* Activate with your product key
* Already have a copy of Tableau Desktop installed? Update your license in the application: Help menu -> Manage Product Keys

To install Pandas & Psycopg2 

```
# conda
$ conda install pandas 
# or or PyPI
$ pip install pandas

$ pip install psycopg2
```
