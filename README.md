# sds192-project1
Project 1 for SDS 192

# Emergency Department Burden Analysis

## Project Overview

This project analyzes patterns in emergency department (ED) burden using the Emergency Department Volume and Capacity dataset. The dataset includes measures such as the number of emergency department visits, available treatment stations, and a calculated ratio of visits per station that represents the relative strain placed on emergency department resources.

The goal of this project is to investigate the following question:

How does the relative burden on emergency departments vary across different health conditions or over time?

By exploring visit counts, treatment capacity, and burden ratios across health condition categories, this analysis aims to identify which types of health conditions may place greater strain on emergency department systems.

## Dataset

The dataset used in this project comes from the U.S. government open data portal:

Emergency Department Volume and Capacity
https://catalog.data.gov/dataset/emergency-department-volume-and-capacity

Some key variables used in this particular analysis include:

- year: reporting year of the observation

- CountyName: county in which the hospital is located

- Category: health condition category associated with ED visits

- Tot_ED_NmbVsts: total number of emergency department visits

- EDStations: number of available treatment stations

- Visits_Per_Station: ratio of visits to stations, representing ED burden

The variable Visits_Per_Station is treated as the primary variable of interest because it reflects the level of demand placed on emergency department capacity.

## File Descriptions

- Project 1.qmd
  - Main analysis file containing data cleaning, visualizations, and interpretation.

- Proposal for Project 1.qmd
  - Initial project proposal describing the research question and variables of interest.

- data folder
  - Contains all datasets used in the project.
      - emergency-department-volume-and-capacity-2021-2023.csv: original dataset
      - data-dictionary.csv: data dictionary describing dataset variables
      - ed_clean.csv: cleaned dataset used for analysis

