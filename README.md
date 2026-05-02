# Overdrawing-Mitigation-Techniques-in-Scatterplot-Visualization

This repository hosts an interactive literature browser for papers related to **Overdraw Mitigation in Scatterplot Visualization**. The website is built with **SurVis**, a browser-based visual literature collection system, and is deployed using GitHub Pages.

## Preview

<p align="center">
  <img src="data/homepage.png" alt="Website preview" width="900">
</p>

## Online Demo
Visit the project website here:

https://zhengyi-lyu.github.io/Overdrawing-Mitigation-Techniques-in-Scatterplot-Visualization/

## Project Purpose

Scatterplots are widely used to visualize data, but overdraw often occur when a large number of points are projected into a limited visual space. This project collects and organizes representative literature on techniques for mitigating scatterplot overdraw.

The goal of this repository is to provide an interactive literature map that supports browsing, filtering, searching, and comparing related studies.
## Main Topics

The collected literature focuses on topics such as:
- Scatterplot overdraw and overplotting mitigation
- Data-space methods, including random sampling, relative-density preservation sampling, relative class density preservation sampling, outlier preservation sampling, spatial separation sampling.
- Visual-space methods, including appearance adjustment, layout adjustment, and animation.
- Hybrid-space methods that combine data abstraction and visual abstraction, including bin aggregation, contour, color weaving, boundary construction.

## Repository Structure

```text
.
├── index.html              # Main website entry
├── about.html              # About page
├── properties.js           # SurVis configuration file
├── js/                     # JavaScript files for the SurVis interface
├── styles/                 # CSS stylesheets
├── fonts/                  # Font resources
└── data/                   # Literature data, generated files, images
