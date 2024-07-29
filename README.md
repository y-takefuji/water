# water

water.py is a program to evaluate diverse characteritics of water quality. The original file is at the following site.

https://catalog.data.gov/dataset/cumberland-piedmont-network-2002-2023-water-quality-data-from-fourteen-park-projects-as-o-

Downloaded file from the site is named 'results.csv'.

waterq is is a PyPI application designed to seamlessly download the results.csv file and provide visualizations of time-series water quality data across a variety of characteristics. 

waterq serves as an interactive platform that allows users to explore and analyze selected water quality characteristics: Acid Neutralizing Capacity (ANC), Fecal Coliform, water temperature, specific conductance, pH, dissolved oxygen saturation, dissolved oxygen (DO), flow, chloride, nitrate nitrogen as NO3, sulfate sulfur as SO4, ammonium nitrogen as NH4, turbidity, sodium, potassium, magnesium, orthophosphate phosphorus as PO4, organic carbon, suspended solids (TSS), calcium, bromide, atrazine, fluoride, precipitation, and Escherichia coli.

waterq empowers users to identify anomalies in water quality data, spanning from historical records to current observations and extending into near-future predictions. Red points indicate anomalies. waterq saves the final result in image file and csv file respectively.

# How to install waterq

$ pip install waterq

# How to run waterq

$ waterq

<img src='https://github.com/y-takefuji/water/raw/main/STRI_RBWF_result.png' height=480 width=640>
