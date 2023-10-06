This is my list of automations used for my Huawei Solar Power.

I'm currently having a 10kW battery.

I use TOU mode to charge my battery with the [EV Smart Charging integration](https://github.com/jonasbkarlsson/ev_smart_charging) and use Maximum Self Consumption for when I'm using the battery to power house grid.

TOU needs to be set to charge all days from 00:00 to 23:59 so when you switch to TOU mode, the battery will imeditately begin charging.

Unfortunately the "Charge from grid" switch does not force the battery to charge when you are in MSC mode and this is why I use this setup.

<img width="570" alt="image" src="https://github.com/woopstar/huawei_solar_home_assistant/assets/2997782/723a88b7-69cd-4a8f-9271-035b0b0aecac">



My settings of EV Smart Charging for my Huawei Solar Battery:

<img width="396" alt="image" src="https://github.com/woopstar/huawei_solar_home_assistant/assets/2997782/469e9cbb-11c7-4df2-a9aa-f4ce2cae5a05">

<img width="325" alt="image" src="https://github.com/woopstar/huawei_solar_home_assistant/assets/2997782/a70df82e-b278-4d1a-8fe2-6c1a9a89e165">
<img width="327" alt="image" src="https://github.com/woopstar/huawei_solar_home_assistant/assets/2997782/4b98f553-9ffc-4305-b1cd-f42153a46e4b">
