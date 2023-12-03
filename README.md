Real Estate Market Analysis

This data science project explores the Brazilian real estate market, focusing on regional differences and the relationship between home size and price.
Overview

The project includes data cleaning, exploratory data analysis (EDA), and visualization using Python and Jupyter notebooks.
Project Structure

lua

|-- data/
|   |-- brasil-real-estate-1.csv
|   |-- brasil-real-estate-2.csv
|-- notebooks/
|   |-- Data_Science_Project.ipynb
|-- visualizations/
|   |-- scatter_mapbox.html
|-- .gitignore
|-- LICENSE
|-- README.md
|-- requirements.txt

Data Sources

    brasil-real-estate-1.csv: Raw data containing information on homes for sale in Brazil.
    brasil-real-estate-2.csv: Additional raw data for analysis.

Analysis Steps

    Data Cleaning:
        Importing and cleaning raw data.
        Handling null values and data types.
        Creating new columns for analysis.

    Exploration:
        Descriptive statistics and visualizations.
        Geographic scatter map using Plotly.
        Histogram of home prices and boxplot of home sizes.
        Bar chart showing mean home prices by region.

    Southern Region Analysis:
        Exploration of the southern region.
        Scatter plot of price vs. area for the state with the most properties.
        Correlation analysis for southern states.

Usage

    Clone the repository:

    bash

git clone https://github.com/yuenfu001/Real-Estate-Market-Analysis.git

Navigate to the project directory:

bash

cd real-estate-analysis

Install dependencies:

bash

pip install -r requirements.txt

Open and run the Jupyter notebook:

bash

    jupyter notebook notebooks/Data_Science_Project.ipynb

Dependencies

    pandas
    numpy
    matplotlib
    seaborn
    plotly
    nbconvert

License

This project is licensed under the MIT License.