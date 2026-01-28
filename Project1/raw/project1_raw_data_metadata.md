# Project 1 — Raw Data Metadata

- filename: Continent_Consumption_TWH.csv
- source: Kaggle — Global Energy Consumption & Renewable Generation
- source_url: https://www.kaggle.com/datasets/jamesarthur/global-energy-consumption-renewable-generation
- download_date: 2026-01-28
- license: CC0 (Public Domain)
- file_size: ~5 KB

## Dataset Structure
- rows: 31
- columns: 12
- time_coverage: 1990–2020
- time_column: Year
- unit: Terawatt-hours (TWh)

## Columns
- Year
- World
- OECD
- BRICS
- Europe
- North America
- Latin America
- Asia
- Pacific
- Africa
- Middle-East
- CIS

## Data Quality Notes
- No missing values detected
- Consistent numeric formatting
- Data types: Year (int), energy values (float)

## Initial Observations
- Global energy consumption increases steadily from 1990 to 2019
- Noticeable drop in 2020 (likely COVID-related)
- Asia shows strong growth compared to other regions

## Next Steps
- Reshape data from wide to long format
- Calculate growth rates by region
- Compare regional shares of global consumption
