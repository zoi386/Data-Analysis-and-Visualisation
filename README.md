# Data-Analysis-and-Visualisation
During five year period from 2015 to 2019 were collected data about World Happiness. The features that were choosen to reflect on Nationes happines around the world are Economy, Health, Family, Goverment corruption etc.
#  Data Cleaning
Data were first cleaned and all datasets were combined together in order to create larger dataset. Unfortunately there's no uniform columns accross all datasets. In order to preserve as much as possible data I have combined those datasets from years that have 'Family column' and those without. This proved to be wrong regardless 'Family column', since this column was influenced by the year in which data were collected more than it was case with others columns.

![image](https://user-images.githubusercontent.com/60197005/150677724-76638564-bdd8-4b6c-8796-9819e01d8749.png)

# Correlation between data
Correlation between columns have been represented by the heatmap.

![image](https://user-images.githubusercontent.com/60197005/150678380-4541fd33-a976-4595-9337-6c36db499013.png)

It is obvious that on Nationes happiness biggest impact have financial security that steams from high GDP or strong Economy, Health and a little less Freedom, while Trust (Goverment Corruption) and Generosity have less than 0.5 coefficient of correlation with Happines Score.

# Visual representation of Happiest Nationes

Since data used in this notebook are collected during 5 years I was interested how countries are ranked in different years? 

![image](https://user-images.githubusercontent.com/60197005/150678626-8504b9e5-d53d-46c7-8d76-9542afc2f761.png)

From previous graph it's  obvious that best performed through obserbavle years is Denmark. Denmark holds one of the first three position, year by year. Well done **Denmark**.

Now let's see what is going on around less happiest nationes.

![image](https://user-images.githubusercontent.com/60197005/150678701-2e50a1d4-7a80-4c32-968f-4078ae43a114.png)
This graph show us how many times cearten country was amoung 10 least happy countries during five year period. Rwanda and Syria hold one of the last teen position through all years.

Data from bottom of the set are more diverse comparing with start, that is whay we have more countries amoung the teen last positioned in differwnt years. 
![image](https://user-images.githubusercontent.com/60197005/150678795-f4219de9-870d-452e-ad3d-645585086248.png)

Finaly we have them all on world map as well.
![image](https://user-images.githubusercontent.com/60197005/150678907-6d8ff3d5-51a2-430e-b23c-0473c5aacebf.png)

Thank you, that would be all. Complete work about this representaion You can find in a notebook.


