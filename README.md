# China County Minimum Wage 2018

This repository provides a county-level minimum wage dataset for China. The dataset records the minimum wage standards in effect on January 1, 2018.

## Data source

The data were manually collected by the author from official websites of provincial, municipal, and county-level governments. Local government notices and information from 2016 to 2018 were checked to identify the minimum wage standards in effect on January 1, 2018.

## File

- `china_mw2018_county.dta`: Stata dataset containing county-level minimum wage standards in China.

## Variables

| Variable | Description |
|---|---|
| `province_cn` | Province name in Chinese |
| `city_cn` | Prefecture-level city name in Chinese |
| `county_cn` | County or district name in Chinese |
| `year` | Year |
| `monthly_mw_yuan` | Monthly minimum wage standard, measured in yuan per month |
| `hourly_mw_yuan` | Hourly minimum wage standard, measured in yuan per hour |
| `province_en` | Province name in English |
| `city_en` | Prefecture-level city name in English |
| `county_en` | County or district name in English |

## Notes

English place names were generated using pinyin transliteration. For ethnic autonomous areas, the English names may not fully correspond to official English translations.

## Citation

If you use this dataset, please cite it as:

Ouyang, Y. (2026). *China county minimum wage 2018* [Data set]. GitHub. https://github.com/yuliaouyang/china-county-minimum-wage-2018
