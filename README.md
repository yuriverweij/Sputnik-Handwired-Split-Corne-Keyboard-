# Sputnik Handwired Split Corne Keyboard

Affordable, handwired split keyboard build (~€20) using a Pro Micro NRF52840 (Nice!nano V2 clone) and repurposed vape batteries (13×34 mm, ~550 mAh). The keyboard is wireless (ZMK, BLE) and can also be used in wired mode via USB. Designed with a focus on sound: the sandwich case with felt between case and plate, plus specifically designed thicc 3D‑printed keycaps, results in a very nice THOCKY sound.

## Features
- Wireless (BLE) with ZMK; also works in wired mode over USB
- Supports [ZMK Studio](https://zmk.dev/docs/features/studio) for keymap configuration
- Prebuilt firmware provided for the reference wiring
- 3D‑printed case and keycaps with ready‑to‑print 3MF files and editable STEP files
  - Case: [MakerWorld](https://makerworld.com/en/models/1836586)
  - Keycaps: [MakerWorld](https://makerworld.com/en/models/1803145)

---

## Media

### Layers (3 images)
- Base layer
  
  ![Base layer](<images and media/base layer.png>)
- Lower layer
  
  ![Lower layer](<images and media/lower layer.png>)
- Raise layer
  
  ![Raise layer](<images and media/raise layer.png>)



### Exploded View (GIF)
![Exploded view](<images and media/exploded view gif.gif>)

### Renders
![Two halves - home perspective](<images and media/2 halves home perspective view.png>)
![Two halves - home view](<images and media/2 halves home view.png>)
![Perspective view front](<images and media/perspective view front.png>)
![Top view - both halves](<images and media/top view both halfes.png>)
![Bottom view - both halves](<images and media/bottom view both halfes.png>)

### Real Pictures
![Both halves - pic 1](<images and media/pictures/both halfes pic 1.jpg>)
![Both halves - pic 2](<images and media/pictures/both halfes pic 2.jpg>)
![Left keyboard - front](<images and media/pictures/left keeb front.jpg>)
![Left keyboard - back](<images and media/pictures/left keeb back.jpg>)

### Sound Test (Video)
- Watch: [Sound test video](https://imgur.com/a/sputnik-split-keyboard-sound-6rZV6Jm)
- For best acoustics:
  - Print the case in PETG with 100% infill
  - Add felt between the plate and the case (avoid plastic-on-plastic contact)
  - Add several layers of felt inside the case to eliminate echoes

---
### BOM and Pricing

IMPORTANT: its M2 not M3 screws and heat inserts
![BOM and pricing](<images and media/BOM and price.png>)
## Build Instructions


Full step‑by‑step instructions are included:
- Build guide (PDF): [Sputnik keyboard Build instructions](<images and media/Sputnik keboard Build instructions.pdf>)
- Wiring diagram: [wiring diagram](<images and media/wiring diagram.jpg>)

Please read the build guide before starting. It includes wiring details, assembly sequence, and notes specific to this handwired design.

## Bill of Materials (BOM)

**WARNING/UPDATE**: When creating BOM i made a mistake, the heat inserts and screws are **actually M2** and **not M3**

This is a handwired build — soldering tools/consumables (iron, solder, flux) are intentionally NOT included. The table lists quantities, links, and estimated pricing. See the BOM image in Media and the build guide PDF for context.

Approximate total cost: ~€20 (as built). Totals from the table: €23.45 (items purchased), €19.02 (used for build).

### BOM and Pricing
![BOM and pricing](<images and media/BOM and price.png>)

### BOM Table

| Item | Link | Amount bought | Amount needed | Price (item) | Price (used) |
|---|---|---:|---:|---:|---:|
| Mechanical Cherry switches (any MX-stem switch will do) | [AliExpress][bom-switches] | 70 | 42 | €8.60 | €5.16 |
| Pro Micro NRF52840 (Nice!nano V2 clone) | [AliExpress][bom-mcu], [Amazon][bom-mcu-amazon] | 1 | 2 | €3.15 | €6.30 |
| Diodes 1N4148 | [AliExpress][bom-diodes] | 50 | 42 | €1.14 | €0.96 |
| M2, 6mm screw | [AliExpress][bom-screws] | 50 | 14 | €2.73 | €0.76 |
| M2 heat inserts (OD 4.2 mm, length 3 mm) | [AliExpress][bom-inserts] | 50 | 14 | €2.76 | €0.77 |
| Kapton tape | [AliExpress][bom-kapton] | 1 | 1 | €1.54 | €1.54 |
| Repurposed vape battery / LiPo 3.7V pouch | n/a | 2 | 2 | — | — |
| Copper wire | [AliExpress][bom-wire] | 1 | 1 | €3.53 | €3.53 |

Total price: €23.45 (items purchased), €19.02 (used for build)

Notes:
- You can also use the original Nice!nano V2; it is compatible with this build.
- Battery sizes 401240 / 501240 / 601240 should fit by dimensions; untested personally.
- Example LiPo listing: [AliExpress LiPo 3.7V pouch (various sizes)][bom-lipo]

[bom-switches]: https://www.aliexpress.com/item/1005007345651159.html?spm=a2g0o.productlist.main.3.1c0c5261aCURnr&algo_pvid=b00fd779-7665-47e9-ae03-470b540f6337&algo_exp_id=b00fd779-7665-47e9-ae03-470b540f6337-2&pdp_ext_f=%7B%22order%22%3A%226394%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005007345651159%22%2C%22orig_item_id%22%3A%221005009261993092%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%215.95%212.98%21%21%2148.40%2124.20%21%40210384cc17589018536814612e5c26%2112000040355282124%21sea%21HR%216267174471%21X%211%210%21n_tag%3A-29919%3Bd%3Ae5d82de9%3Bm03_new_user%3A-29895&curPageLogUid=zCC6svikv5Hc&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007345651159%7C_p_origin_prod%3A1005009261993092
[bom-mcu]: https://www.aliexpress.com/item/1005006995289476.html?spm=a2g0o.productlist.main.3.54714221NO3mPU&algo_pvid=018aecb1-eafc-46ed-bf24-799c5e0c8c98&algo_exp_id=018aecb1-eafc-46ed-bf24-799c5e0c8c98-6&pdp_ext_f=%7B%22order%22%3A%221766%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005006995289476%22%2C%22orig_item_id%22%3A%221005006599766097%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%216.30%213.15%21%21%2151.30%2125.65%21%402103835c17589020591883661e413f%2112000038985691707%21sea%21HR%216267174471%21X%211%210%21n_tag%3A-29919%3Bd%3Ae5d82de9%3Bm03_new_user%3A-29895&curPageLogUid=VJ4Cad4XkmFS&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006995289476%7C_p_origin_prod%3A1005006599766097
[bom-diodes]: https://www.aliexpress.com/item/1005006245109375.html?spm=a2g0o.productlist.main.7.5f80648d0kGwN4&algo_pvid=28c31425-6c38-46a6-8a23-bc7315cb9f00&algo_exp_id=28c31425-6c38-46a6-8a23-bc7315cb9f00-6&pdp_ext_f=%7B%22order%22%3A%22973%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%211.75%211.14%21%21%2114.21%219.26%21%402103919917589021056008905e2bbe%2112000036448323916%21sea%21HR%216267174471%21X%211%210%21n_tag%3A-29919%3Bd%3Ae5d82de9%3Bm03_new_user%3A-29895&curPageLogUid=OhJwy5f5LVsx&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006245109375%7C_p_origin_prod%3A
[bom-screws]: https://www.aliexpress.com/item/1005005070119421.html?spm=a2g0o.cart.0.0.29ce38daTZImhU&mp=1&pdp_npi=5%40dis%21EUR%21EUR%202.73%21EUR%202.73%21%21EUR%202.73%21%21%21%40211b81a317589021869796790e7203%2112000031519353292%21ct%21HR%216267174471%21%211%210&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D
[bom-inserts]: https://www.aliexpress.com/item/1005003582355741.html?spm=a2g0o.cart.0.0.29ce38daTZImhU&mp=1&pdp_npi=5%40dis%21EUR%21EUR%202.83%21EUR%202.76%21%21EUR%202.76%21%21%21%40211b81a317589021869796790e7203%2112000026370649726%21ct%21HR%216267174471%21%211%210
[bom-kapton]: https://www.aliexpress.com/item/1005007518587827.html?spm=a2g0o.productlist.main.2.202f49e3GVOXp0&algo_pvid=b11967b5-32c6-4440-93a4-052201d52ac3&algo_exp_id=b11967b5-32c6-4440-93a4-052201d52ac3-4&pdp_ext_f=%7B%22order%22%3A%2216925%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%211.54%211.54%21%21%2112.49%2112.49%21%402103891017590609061623435ece05%2112000041103956429%21sea%21HR%216267174471%21X%211%210%21n_tag%3A-29919%3Bd%3Ae5d82de9%3Bm03_new_user%3A-29895&curPageLogUid=FLnTGx29WStB&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007518587827%7C_p_origin_prod%3A
[bom-wire]: https://www.aliexpress.com/item/1005009078359338.html?spm=a2g0o.order_list.order_list_main.56.47741802kB9uqg
[bom-mcu-amazon]: https://www.amazon.com/Development-Bluetooth-Management-Module%EF%BC%8CNano-Compatible/dp/B0F1KDBDHQ?th=1
[bom-lipo]: https://www.aliexpress.com/item/32706541598.html?spm=a2g0o.productlist.main.1.6c9255ca3SqWTn&algo_pvid=5ca5e224-6927-48ec-9224-5f801eb8a34f&algo_exp_id=5ca5e224-6927-48ec-9224-5f801eb8a34f-0&pdp_ext_f=%7B%22order%22%3A%222%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%218.07%217.50%21%21%219.24%218.59%21%40211b619a17591477346181228e9763%2112000048362357032%21sea%21HR%216267174471%21X%211%210%21n_tag%3A-29919%3Bd%3Ae5d82de9%3Bm03_new_user%3A-29895&curPageLogUid=WjLGl3y7nFDC&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A32706541598%7C_p_origin_prod%3A

## Firmware
- Prebuilt UF2 files are provided for the reference wiring:
  - Left half: [corne_hw_left-nice_nano_v2-zmk.uf2](<firmware/ready to flash/corne_hw_left-nice_nano_v2-zmk.uf2>)
  - Right half: [corne_hw_right-nice_nano_v2-zmk.uf2](<firmware/ready to flash/corne_hw_right-nice_nano_v2-zmk.uf2>)
- If you wire according to the provided diagram, you can use the prebuilt firmware directly.
- If you wire it differently or use a different controller, you will need to build your own ZMK firmware. See:
  - ZMK docs (User setup): [zmk.dev/docs/user-setup](https://zmk.dev/docs/user-setup)
  - ZMK docs (Overview): [zmk.dev/docs](https://zmk.dev/docs)

### Flashing (UF2)
1. Put the Nice!nano into bootloader mode (double‑tap reset).
2. A USB drive should appear; drag‑and‑drop the appropriate `.uf2` file.
3. Repeat for the other half.

## ZMK Studio
This build supports ZMK Studio for convenient keymap adjustments:
- ZMK Studio: [zmk.dev/docs/features/studio](https://zmk.dev/docs/features/studio)

## Case and Keycaps (3D Printing)
You have ready‑to‑print 3MF files and editable STEP files:
  - Case: [MakerWorld](https://makerworld.com/en/models/1836586)
  - Keycaps: [MakerWorld](https://makerworld.com/en/models/1803145)


## Battery
- You can use repurposed vape batteries, or any battery that fits the plate cavity.
- Cavity dimensions (from plate to bottom case):
  - Height: 13 mm
  - Length: ~40 mm (up to ~48 mm if you install the MCU cover first, then add the battery)
  - Width: ~12 mm
- Any battery that fits within this space will work.

### Power switch (optional)
Add an **SPST switch in series with the battery's positive (B+) lead** to
turn each half off. Cut the battery's positive wire and route it through the
switch instead of soldering it straight to the `B+` pad:

```
Battery (+) ──── [ SWITCH ] ──── B+ pad
Battery (−) ─────────────────── B− pad
```

- Wire it **in series (inline)**, never across `B+`/`B−` — bridging the two
  pads would short the battery.
- Only the battery is switched. With the switch OFF and USB plugged in, the
  board still runs off USB **and the battery still charges** through the
  Nice!nano's charging circuit. So: switch OFF = run/charge on USB, switch
  ON = run on battery when unplugged.
- An **SPST** switch (2 pins) is all you need. An **SPDT** (3-pin) switch also
  works — just use the middle (common) pin plus one outer pin.
- Current is only a few mA, so any small slide/toggle switch works; pick one
  that fits your case.
- This is a split keyboard, so add **one switch per half** (each half has its
  own Nice!nano and battery).
- Solder with the battery disconnected where possible to avoid accidental shorts.

## Repository Layout
- Firmware
  - Prebuilt UF2s: [`firmware/ready to flash/`](<firmware/ready to flash/>)
  - Config: [`firmware/zmk-config/`](<firmware/zmk-config/>)
- 3D Models
  - Ready to print: [`Ready to print files set/`](<Ready to print files set/>)
  - Case STEP: [`case step files/`](<case step files/>)
  - Keycaps STEP: [`keycaps step files/`](<keycaps step files/>)
  - Keycaps 3MF: [`keycaps 3mf/`](<keycaps 3mf/>)
- Media & docs: [`images and media/`](<images and media/>)
