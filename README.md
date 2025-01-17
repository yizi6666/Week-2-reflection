# Root Directory
# Scholarly Migration Dataset Analysis

This repository contains resources and instructions for setting up the system and running data analysis on the **Scholarly Migration Dataset** for the period 1998–2020. The dataset includes international migration rates and flows for scholars from 210 countries and is based on Scopus and OpenAlex bibliometric data.

## System Configuration

### Prerequisites

- **Operating System:** Compatible with Linux, macOS, or Windows.
- **Python Version:** Python 3.9 or higher.
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - SQLAlchemy
  - psycopg2
  - scikit-learn
  - GeoPandas (for geographical processing)
- **Database:**
  - PostgreSQL (used for bibliometric data processing).

### Installation Steps

1. Install Python 3.9 or higher from [python.org](https://www.python.org/).
2. Set up a PostgreSQL database:
   - Install PostgreSQL following the instructions for your operating system.
   - Import bibliometric data provided by the Competence Network for Bibliometrics using SQL scripts or the PostgreSQL `psql` command.
3. Install Python dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn SQLAlchemy psycopg2 scikit-learn geopandas
