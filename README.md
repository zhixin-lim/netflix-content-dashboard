# Netflix Content Dashboard

An interactive Tableau dashboard exploring the composition and characteristics of Netflix's movie and TV show catalogue.

## Dashboard Preview

![Netflix Content Dashboard](images/Netflix%20Dashboard.png)

## Project Overview

This project visualises Netflix title metadata through an interactive dashboard. Users can explore individual titles alongside broader distributions across content types, ratings, genres, production countries and release years.

A title selector connects the individual title details to the wider dashboard, allowing users to explore the catalogue interactively.

## Dashboard Features

- **Title details:** Explore a selected title's type, rating, release year, duration, date added, genre and description.
- **Production countries:** View the geographic distribution of titles by their recorded production countries.
- **Content ratings:** Compare the distribution of audience and maturity ratings.
- **Genre distribution:** Explore the most frequently listed genre categories.
- **Movies vs. TV shows:** Compare the composition of the catalogue.
- **Release years:** Explore how the catalogue is distributed across release years.

## Tools & Skills

- **Tableau:** Dashboard development, data visualisation, formatting and interactivity.
- **Excel / Power Query:** Data preparation for the country-level visualisation.

## Data Source

Dataset: [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains title-level metadata, including content type, country, release year, rating, duration, genre and description.

## Data Preparation

The country field contains multiple production countries for some titles. For the geographic visualisation, these values were separated into individual title-country records, allowing a title to be associated with multiple countries.

Titles without a recorded country are excluded from the map. Country-level counts represent distinct titles associated with each country and therefore should not be summed to estimate the total number of unique titles.

## Notes & Limitations

This project is primarily a data visualisation and dashboard design exercise. The visualisations support interactive exploration of the dataset rather than establishing causal relationships or making predictions.

The dataset represents a historical snapshot and may not reflect Netflix's current catalogue or availability by region.

