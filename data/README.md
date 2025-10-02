# ATUS Data Directory

## Overview

This directory contains the American Time Use Survey (ATUS) data files downloaded from the Bureau of Labor Statistics, covering the years 2003-2024. The ATUS provides nationally representative estimates of how Americans spend their time, with detailed information about daily activities including household work, childcare, employment, and leisure activities.

## Data Contents

### Activity Files (2003-2024)
- **atusact_YYYY.dat**: Annual activity files containing detailed time diary data for each survey year
- Each file includes respondent activities with start/stop times, activity codes, and location information
- Activities are coded using a standardized classification system with over 400 specific activity types

### Supporting Documentation
- **Data Dictionaries**: Complete variable definitions and coding schemes for all data files
- **Activity Lexicon**: Detailed descriptions of activity codes and hierarchical classifications
- **Respondent Summary**: Demographic characteristics and sample composition for each survey year

## Survey Design

- **Sample Size**: Approximately 9,000-12,000 respondents annually
- **Age Range**: Americans aged 15 and older
- **Collection Method**: Computer-assisted telephone interviews
- **Time Period**: 24-hour retrospective time diary for one designated day
- **Sampling**: Nationally representative probability sample

## Key Variables

- **Household Activities**: Cleaning, cooking, laundry, maintenance, shopping
- **Demographics**: Age, gender, education, employment status, household composition
- **Time Allocation**: Minutes spent on each activity category
- **Day Information**: Day of week, holiday status, seasonality

## File Formats

All data files are provided in fixed-width ASCII format (.dat) with accompanying format files that specify column positions and variable types. Data processing scripts in Lab 1 will convert these files into analysis-ready formats.

---

*Source: U.S. Bureau of Labor Statistics, American Time Use Survey*
