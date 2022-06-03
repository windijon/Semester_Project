# Proposal for Semester Project

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                              |
|----------------|---------------------------------- |
| **Data:**      | Wild Boar Movement Data           |
| **Title:**     | Spatial Analyses of wild boars data regarding on psycological patterns           |
| **Student 1:** | Jonas Michael Windisch            |
| **Student 2:** | Johannes Quente                   |

## Abstract 
The following project work deals with given wild-boar data and examine the movement patterns of (at least) four individuals. The movement patterns have been analyzed regarding possible behavioural constraints that are being looked for due to additional underlaying shape-format datasets like (settlements, streets and different land use categories). Further the data is being compared on the different properties of the individuals, like the activity (day-night, pace).

## Research Questions
The research question been asked is: How can the different environments (settlements, streets and different land use categories) been contextualized with the activity-patterns of the wild boar-data. How can this be conceptualized, modelled and further implemented in suitable visualizations to show behavioral patterns given to a certain environmental context and help to answer questions like “What does wild boar fear?” or “What are the behavioral constraints of wild boars?”.

## Results / products
We do expect some kind of special heat maps, like behavioral patterns regarding (resting time, running (pace), feeding, hourly activity patterns) in relation to different environmental contexts (settlements, streets and different land use categories). Therefore, we can potentially derive some kind of psychological patterns of wild boar and estimate ratings like “the most ruthless wild boar”, “the fastest wild boar", “the most fearful wild boar", given that e.g. settlements are generally a stress factor for animals. Cross-scale movement analysis of speed, turning angles, sinuosity.

## Data
For this project we need the following data: wild boar data given by the course administration of Patterns & Trends in Environmental Data, areal statistics data & orthoimages given by swisstopo (open access) and Topographic Vector Maps given by geovite.ethz.ch (open access). The orthoimages are given as a tif file, the other are given as vector dataset.

## Analytical concepts
After importing all the data, we explore our data. Then a 10 m buffer zone is created around all human-made artificial objects (settlements, streets, etc.). Next, the trajectories of the wild boars are compared with the received artificial objects: How close do the wild boar approximate the settlements? The land use categories and the trajectories are plotted on an orthoimage to visualize where and how long the wild boars stays in certain location. With a heat map the daily schedule of the wild boar movement can be shown.

## R concepts
It is expected that the R packages used in the lessons are sufficient (readr, dplyr, ggplot2, sf, terra, lubridate, etc.). We create a RStudio Project and are up-loading and committing our progress on github (https://github.com/windijon/ZHAW-Patterns-Trends-Semester-Project.git).

## Risk analysis
Timemangement could be a problem due to other duties. Plan B: Only answering part-questions. 

## Questions? 
--> Which packages do you recommend? 
--> Is this too abitious? 
--> How related has this project to be regarding secondary literatur?
