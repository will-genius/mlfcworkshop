
# Accident Blackspot Mapping & Safe Route Identification

This project uses **Kenyas road Traffic crash data between 2012 and 2023** and **OpenStreetMap (OSM) road networks** to identify and plot accident blackspots in  Kenya and to suggest **safer driving routes** that minimize exposure to high-risk road segments.

---

## 📌 Features

**Accident Blackspot Mapping**

  * Geospatial visualization of crash locations in the country.

**Crash Data Analysis**

  * Distribution of crashes by month, hour, and day of week.
  * patterns visualized using bar plots and heatmaps.

**Safe Route Identification**

  * Assigns a **risk score** to each road segment based on crash history.
  * This aids in Computing both:

    * **Shortest Route (distance-based)**
    * **Safer Route (risk-aware, balancing crash history & distance)**
  * Routes visualized on interactive maps using **Folium**.


---

## 🏗️ Tech Stack

* **Python 3**
* **Libraries:**

  * [osmnx](https://github.com/gboeing/osmnx) – road network analysis
  * [networkx](https://networkx.org/) – graph algorithms (shortest path, safe route)
  * [folium](https://python-visualization.github.io/folium/) – interactive maps
  * [geopandas](https://geopandas.org/) – spatial data processing
  * [matplotlib](https://matplotlib.org/) – crash data visualization

---

##  Usage

### Setup environment

```bash
git clone https://github.com/will-genius/mlfcworkshop.git
cd mlfcworkshop
```

### Run Accident_Black_spot_Mapping Notebook

```
Accident_Black_spot_Mapping_in_Kenya.ipynb
```
---

## Sample Outputs

* Crash counts by month & hour
* Heatmap of crash distribution (Day vs Hour)
* Folium maps showing:

  * crash hotspots
  * Safe vs shortest driving routes in Nairobi

---

## Future Work

* Extend system to **other Kenyan cities**.
* Add A regex function to enable route identification without proper name spelling

---

## Acknowledgments

* **OpenStreetMap** for road data.
* **world Bank Mocrodata Library** for crash dataset.
