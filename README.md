# Short Term Air Temperature By Using ML

## An Experimental Study to Understand How AI Learns Atmospheric Patterns

This repository implements machine learning models for short-term (1-7 day) air temperature forecasting using historical hourly weather data for an Indian city (Chandigarh, ~30.76°N, 76.82°E). We train simple regression to deep learning models and apply explainable AI (XAI) to reveal hidden atmospheric patterns in temperature, pressure, wind, and cycles.

### Project Objectives (From Proposal)
- Collect and prepare 5-10 years of hourly and daily data. 
- Build and compare models (target MAE: 1.5-2.0°C for 24-72h forecasts).
- Use XAI to discover non-obvious patterns (e.g., wind-time cycle interactions).
- Deliver reproducible code, accurate temperature forecasting model, hidden pattern discovery, research report, and zero-cost which is proof of concept

### Quick Setup for Reproducibility
1. Clone: `git clone https://github.com/xnih05/Short-term-air-temperature-by-using-ML.git`
2. Install: `pip install -r requirements.txt`
3. Run: Open `notebooks/01_data_preparation.ipynb` in Jupyter.

### Data
- Source: Open Meteo API (temperature_2m, pressure_msl, wind_speed_10m, etc.).
- File: `data/open-meteo-chandigarh-hourly.csv` (2015-2025).

### Team
- Nihal Singh (Team Leader)
- Yashmeen Paul
- Naina Vajpayee
- Saksham Thakur
- Guidance: Asst. Prof. Ayush, Dept. of Engineering

**Research Note**: This project demonstrates accessible Machine Learning for weather forecasting, bypassing complex physics models. Ideal for student experiments—extend to multi-city or real-time predictions for papers.

## License
MIT
