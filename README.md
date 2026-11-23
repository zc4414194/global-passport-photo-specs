# Global Biometric Passport & Visa Photo Specifications (121 Countries)

**An open-source, machine-readable reference dataset of official ICAO-compliant passport, visa, and national ID photo dimensions (mm, 300 DPI pixels, biometric head ratios, and background colors) across 121 countries (2411+ official specifications).**

[![Live Generator](https://img.shields.io/badge/Free_Online_Maker-dopic.app-0284c7?style=flat-square)](https://dopic.app/)
[![Countries](https://img.shields.io/badge/Countries-121-15803d?style=flat-square)](#full-country-directory)
[![Specifications](https://img.shields.io/badge/Official_Specs-2411%2B-0f172a?style=flat-square)](specs.json)
[![License: MIT](https://img.shields.io/badge/License-MIT-475569?style=flat-square)](LICENSE)

---

## Free Browser-Local Passport Photo Generator

Need to generate a 300 DPI compliant passport photo or 4×6" print sheet immediately? Use the free, 100% browser-local tool powered by this exact dataset (zero image uploads, no watermark):

👉 **[Create Official Passport & Visa Photos on Dopic.app](https://dopic.app/)**

---

## Top 20 Most Searched Passport Photo Specifications

| Country | Primary Official Spec | Physical Size | Digital Size (300 DPI) | Head Ratio | Background | Free Online Tool |
| :--- | :--- | :---: | :---: | :---: | :---: | :--- |
| **United States** (`US`) | U.S. Passport & Visa (2x2") | `51 × 51 mm` | `600 × 600 px` | 50%-69% | `#FFFFFF` | [Generate Free →](https://dopic.app/) |
| **United Kingdom** (`GB`) | Standard Biometric Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/gb/) |
| **Germany** (`DE`) | Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/de/) |
| **France** (`FR`) | French Passport (ICAO Standard) | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#E5E7EB` | [Generate Free →](https://dopic.app/fr/) |
| **Japan** (`JP`) | Japanese Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/jp/) |
| **China** (`CN`) | PRC Ordinary Passport Photo | `33 × 48 mm` | `390 × 567 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/cn/) |
| **South Korea** (`KR`) | Republic of Korea Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/kr/) |
| **Canada** (`CA`) | Canadian Passport Photo | `50.8 × 63.5 mm` | `600 × 750 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/ca/) |
| **Australia** (`AU`) | Australian Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/au/) |
| **India** (`IN`) | Indian Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/in/) |
| **Singapore** (`SG`) | Singapore Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/sg/) |
| **Spain** (`ES`) | Biometric Passport | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/es/) |
| **Italy** (`IT`) | Electronic Passport (New Model) | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/it/) |
| **Netherlands** (`NL`) | Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/nl/) |
| **Brazil** (`BR`) | Standard Brazilian Passport | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/br/) |
| **Mexico** (`MX`) | Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/mx/) |
| **Vietnam** (`VN`) | Ordinary Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/vn/) |
| **Thailand** (`TH`) | Passport | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/th/) |
| **United Arab Emirates** (`AE`) | Standard Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/ae/) |
| **Saudi Arabia** (`SA`) | Electronic Passport Photo | `35 × 45 mm` | `413 × 531 px` | 70%-80% | `#FFFFFF` | [Generate Free →](https://dopic.app/sa/) |

---

## Machine-Readable JSON Dataset (`specs.json`)

Developers, AI agents, and travel apps can consume [`specs.json`](specs.json) directly under the MIT License:

```json
{
  "country_code": "US",
  "country_name": "United States",
  "total_specs": 25,
  "primary_spec": {
    "id": "us_passport",
    "name": "U.S. Passport & Visa (2x2\")",
    "width_mm": 51,
    "height_mm": 51,
    "width_px_300dpi": 600,
    "height_px_300dpi": 600,
    "dpi": 300,
    "head_ratio": "50%-69%",
    "background_hex": "#FFFFFF"
  },
  "online_generator_url": "https://dopic.app/"
}
```

---

## Why 4×6" Multi-Photo Print Sheets Save 95%

Retail photo counters (CVS, Walgreens, Boots, 7-Eleven) typically charge **$12–$17** for a set of 2 passport photos. Using a standard **4×6 inch (102×152 mm) 300 DPI print sheet** tiled with 4 to 8 compliant photos lets you print at any local photo kiosk or convenience store for **$0.25–$0.49**.

All country tools on **[Dopic.app](https://dopic.app/)** automatically generate both single digital biometric files and 4×6" print-ready sheets 100% locally in your browser.

---

## Full Country Directory (121 Countries)

<details>
<summary><strong>Click to expand all 121 countries & official dimensions</strong></summary>

| Country | Specs Covered | Primary Physical Size | Primary 300 DPI Size | Direct Portal |
| :--- | :---: | :---: | :---: | :--- |
| Afghanistan (`AF`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AF Tool](https://dopic.app/af/) |
| Albania (`AL`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AL Tool](https://dopic.app/al/) |
| Algeria (`DZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open DZ Tool](https://dopic.app/dz/) |
| Angola (`AO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AO Tool](https://dopic.app/ao/) |
| Argentina (`AR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AR Tool](https://dopic.app/ar/) |
| Armenia (`AM`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AM Tool](https://dopic.app/am/) |
| Australia (`AU`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AU Tool](https://dopic.app/au/) |
| Austria (`AT`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AT Tool](https://dopic.app/at/) |
| Azerbaijan (`AZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AZ Tool](https://dopic.app/az/) |
| Bahrain (`BH`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BH Tool](https://dopic.app/bh/) |
| Bangladesh (`BD`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BD Tool](https://dopic.app/bd/) |
| Belarus (`BY`) | 20 specs | `40 × 50 mm` | `472 × 591 px` | [Open BY Tool](https://dopic.app/by/) |
| Belgium (`BE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BE Tool](https://dopic.app/be/) |
| Bolivia (`BO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BO Tool](https://dopic.app/bo/) |
| Bosnia and Herzegovina (`BA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BA Tool](https://dopic.app/ba/) |
| Brazil (`BR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BR Tool](https://dopic.app/br/) |
| Bulgaria (`BG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open BG Tool](https://dopic.app/bg/) |
| Cambodia (`KH`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open KH Tool](https://dopic.app/kh/) |
| Cameroon (`CM`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CM Tool](https://dopic.app/cm/) |
| Canada (`CA`) | 20 specs | `50.8 × 63.5 mm` | `600 × 750 px` | [Open CA Tool](https://dopic.app/ca/) |
| Chile (`CL`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CL Tool](https://dopic.app/cl/) |
| China (`CN`) | 20 specs | `33 × 48 mm` | `390 × 567 px` | [Open CN Tool](https://dopic.app/cn/) |
| Colombia (`CO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CO Tool](https://dopic.app/co/) |
| Costa Rica (`CR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CR Tool](https://dopic.app/cr/) |
| Croatia (`HR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open HR Tool](https://dopic.app/hr/) |
| Cyprus (`CY`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CY Tool](https://dopic.app/cy/) |
| Czech Republic (`CZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CZ Tool](https://dopic.app/cz/) |
| Denmark (`DK`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open DK Tool](https://dopic.app/dk/) |
| Dominican Republic (`DO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open DO Tool](https://dopic.app/do/) |
| Ecuador (`EC`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open EC Tool](https://dopic.app/ec/) |
| Egypt (`EG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open EG Tool](https://dopic.app/eg/) |
| El Salvador (`SV`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SV Tool](https://dopic.app/sv/) |
| Estonia (`EE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open EE Tool](https://dopic.app/ee/) |
| Ethiopia (`ET`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open ET Tool](https://dopic.app/et/) |
| European Union (`EU`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open EU Tool](https://dopic.app/eu/) |
| Finland (`FI`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open FI Tool](https://dopic.app/fi/) |
| France (`FR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open FR Tool](https://dopic.app/fr/) |
| Georgia (`GE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open GE Tool](https://dopic.app/ge/) |
| Germany (`DE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open DE Tool](https://dopic.app/de/) |
| Ghana (`GH`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open GH Tool](https://dopic.app/gh/) |
| Greece (`GR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open GR Tool](https://dopic.app/gr/) |
| Guatemala (`GT`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open GT Tool](https://dopic.app/gt/) |
| Honduras (`HN`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open HN Tool](https://dopic.app/hn/) |
| Hong Kong (`HK`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open HK Tool](https://dopic.app/hk/) |
| Hungary (`HU`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open HU Tool](https://dopic.app/hu/) |
| Iceland (`IS`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IS Tool](https://dopic.app/is/) |
| India (`IN`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IN Tool](https://dopic.app/in/) |
| Indonesia (`ID`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open ID Tool](https://dopic.app/id/) |
| Iran (`IR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IR Tool](https://dopic.app/ir/) |
| Iraq (`IQ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IQ Tool](https://dopic.app/iq/) |
| Ireland (`IE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IE Tool](https://dopic.app/ie/) |
| Israel (`IL`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IL Tool](https://dopic.app/il/) |
| Italy (`IT`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open IT Tool](https://dopic.app/it/) |
| Ivory Coast (`CI`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CI Tool](https://dopic.app/ci/) |
| Japan (`JP`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open JP Tool](https://dopic.app/jp/) |
| Jordan (`JO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open JO Tool](https://dopic.app/jo/) |
| Kazakhstan (`KZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open KZ Tool](https://dopic.app/kz/) |
| Kenya (`KE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open KE Tool](https://dopic.app/ke/) |
| Kuwait (`KW`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open KW Tool](https://dopic.app/kw/) |
| Kyrgyzstan (`KG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open KG Tool](https://dopic.app/kg/) |
| Laos (`LA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open LA Tool](https://dopic.app/la/) |
| Latvia (`LV`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open LV Tool](https://dopic.app/lv/) |
| Lebanon (`LB`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open LB Tool](https://dopic.app/lb/) |
| Lithuania (`LT`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open LT Tool](https://dopic.app/lt/) |
| Luxembourg (`LU`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open LU Tool](https://dopic.app/lu/) |
| Macau (`MO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MO Tool](https://dopic.app/mo/) |
| Madagascar (`MG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MG Tool](https://dopic.app/mg/) |
| Malaysia (`MY`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MY Tool](https://dopic.app/my/) |
| Malta (`MT`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MT Tool](https://dopic.app/mt/) |
| Mexico (`MX`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MX Tool](https://dopic.app/mx/) |
| Mongolia (`MN`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MN Tool](https://dopic.app/mn/) |
| Morocco (`MA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MA Tool](https://dopic.app/ma/) |
| Mozambique (`MZ`) | 21 specs | `35 × 45 mm` | `413 × 531 px` | [Open MZ Tool](https://dopic.app/mz/) |
| Myanmar (`MM`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MM Tool](https://dopic.app/mm/) |
| Nepal (`NP`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open NP Tool](https://dopic.app/np/) |
| Netherlands (`NL`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open NL Tool](https://dopic.app/nl/) |
| New Zealand (`NZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open NZ Tool](https://dopic.app/nz/) |
| Nicaragua (`NI`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open NI Tool](https://dopic.app/ni/) |
| Nigeria (`NG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open NG Tool](https://dopic.app/ng/) |
| North Macedonia (`MK`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open MK Tool](https://dopic.app/mk/) |
| Norway (`NO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open NO Tool](https://dopic.app/no/) |
| Oman (`OM`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open OM Tool](https://dopic.app/om/) |
| Pakistan (`PK`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open PK Tool](https://dopic.app/pk/) |
| Panama (`PA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open PA Tool](https://dopic.app/pa/) |
| Paraguay (`PY`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open PY Tool](https://dopic.app/py/) |
| Peru (`PE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open PE Tool](https://dopic.app/pe/) |
| Philippines (`PH`) | 20 specs | `51 × 51 mm` | `602 × 602 px` | [Open PH Tool](https://dopic.app/ph/) |
| Poland (`PL`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open PL Tool](https://dopic.app/pl/) |
| Portugal (`PT`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open PT Tool](https://dopic.app/pt/) |
| Qatar (`QA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open QA Tool](https://dopic.app/qa/) |
| Romania (`RO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open RO Tool](https://dopic.app/ro/) |
| Russia (`RU`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open RU Tool](https://dopic.app/ru/) |
| Saudi Arabia (`SA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SA Tool](https://dopic.app/sa/) |
| Senegal (`SN`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SN Tool](https://dopic.app/sn/) |
| Serbia (`RS`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open RS Tool](https://dopic.app/rs/) |
| Singapore (`SG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SG Tool](https://dopic.app/sg/) |
| Slovakia (`SK`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SK Tool](https://dopic.app/sk/) |
| Slovenia (`SI`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SI Tool](https://dopic.app/si/) |
| Somalia (`SO`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SO Tool](https://dopic.app/so/) |
| South Africa (`ZA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open ZA Tool](https://dopic.app/za/) |
| South Korea (`KR`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open KR Tool](https://dopic.app/kr/) |
| Spain (`ES`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open ES Tool](https://dopic.app/es/) |
| Sri Lanka (`LK`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open LK Tool](https://dopic.app/lk/) |
| Sweden (`SE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open SE Tool](https://dopic.app/se/) |
| Switzerland (`CH`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open CH Tool](https://dopic.app/ch/) |
| Taiwan (`TW`) | 4 specs | `35 × 45 mm` | `413 × 531 px` | [Open TW Tool](https://dopic.app/tw/) |
| Tajikistan (`TJ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open TJ Tool](https://dopic.app/tj/) |
| Tanzania (`TZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open TZ Tool](https://dopic.app/tz/) |
| Thailand (`TH`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open TH Tool](https://dopic.app/th/) |
| Tunisia (`TN`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open TN Tool](https://dopic.app/tn/) |
| Turkey (`TR`) | 20 specs | `45 × 60 mm` | `531 × 709 px` | [Open TR Tool](https://dopic.app/tr/) |
| Turkmenistan (`TM`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open TM Tool](https://dopic.app/tm/) |
| Uganda (`UG`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open UG Tool](https://dopic.app/ug/) |
| Ukraine (`UA`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open UA Tool](https://dopic.app/ua/) |
| United Arab Emirates (`AE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open AE Tool](https://dopic.app/ae/) |
| United Kingdom (`GB`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open GB Tool](https://dopic.app/gb/) |
| United States (`US`) | 25 specs | `51 × 51 mm` | `600 × 600 px` | [Open US Tool](https://dopic.app/) |
| Uruguay (`UY`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open UY Tool](https://dopic.app/uy/) |
| Uzbekistan (`UZ`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open UZ Tool](https://dopic.app/uz/) |
| Venezuela (`VE`) | 20 specs | `35 × 45 mm` | `413 × 531 px` | [Open VE Tool](https://dopic.app/ve/) |
| Vietnam (`VN`) | 21 specs | `35 × 45 mm` | `413 × 531 px` | [Open VN Tool](https://dopic.app/vn/) |

</details>

---

## Maintained By

Maintained by **[Dopic.app](https://dopic.app/)** — Privacy-first, 100% browser-local photo studio:

- **[Global Passport & Visa Photo Maker](https://dopic.app/)** — 121 countries, 300 DPI print sheets
- **[AI Background Remover](https://dopic.app/tools/cutout/)** — Hair-level transparent PNG cutout
- **[ID Card Privacy Redact & Watermark](https://dopic.app/tools/redact/)** — Blur sensitive ID numbers & add anti-misuse watermarks
- **[Transparent Signature Extractor](https://dopic.app/tools/signature/)** — Extract paper signatures to transparent PNG
- **[Lossless Image Compressor](https://dopic.app/tools/compress/)** — Compress to exact 20KB / 50KB / 100KB limits locally

## License

MIT License — see [LICENSE](LICENSE) for details.
