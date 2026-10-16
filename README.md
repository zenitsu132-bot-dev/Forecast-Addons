# Forecast Add-ons

A plugin for Storm Central that adds extra weather layers to the Radar and Air maps. It is a single JSON file with no code, so it only adds map layers and can't run anything on your device.

# Layers

All layers are off by default except Fronts (Day 1). Turn on whichever ones you want.

Layer	Days	What it shows
Fronts	1, 2, 3	Forecast fronts from the NOAA Weather Prediction Center (WPC)
Highs and lows	1	Forecast high and low pressure centers
Excessive Rainfall	1, 2, 3	WPC Excessive Rainfall Outlook (flash flood risk areas)
Flash Flooding Possible	1, 2, 3	Areas where heavy rain or flash flooding is possible
Severe Thunderstorms Possible	1, 2, 3	Areas where severe thunderstorms are possible
Snow Depth	Current	Modeled snow depth for the lower 48 states
Install
Open Storm Central and go to Settings → Add-ons.
Paste zenitsu132-bot-dev/Forecast-Addons (or a link to this repo's stormcentral.json).
Install it, then choose which layers to show.

If you update the plugin and the app still shows an old version, remove the add-on and add it again.

# Data and updates

The plugin stores links to NOAA map services, not the data itself, so the layers update on their own whenever NOAA publishes new information. "Day 1" always means the current Day 1 forecast.

Forecast layers (fronts, highs and lows, flash flooding, severe thunderstorms): NOAA/NWS Weather Prediction Center
Excessive Rainfall Outlook: NOAA/NWS Weather Prediction Center
Snow Depth: NOAA/NWS National Operational Hydrologic Remote Sensing Center (NOHRSC). It covers the lower 48 states, and the map may look mostly empty outside of snow season.
Notes
This plugin is not affiliated with NOAA, the National Weather Service, or Storm Central.
For safety decisions, always check official forecasts and warnings at weather.gov.
If a layer shows nothing, the NOAA service may be temporarily down or may have changed.

# Author

Made by Zenitsu132.
