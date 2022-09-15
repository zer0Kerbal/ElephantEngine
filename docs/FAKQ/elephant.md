# Elephant vs stock engines

| name                      | thrust | (0/1) isp |      weight |   size | gimbal |  GRS  | MultiMode |  Alt  |
| :------------------------ | -----: | --------: | ----------: | -----: | :----: | :---: | :-------: | :---: |
| ***Stock***               |  ----- |  -------- |       ----- |   ---- |  ----  |  ---  |  -------  |  --   |
| 48-7S "Spark"             |     20 |   320/265 |        0.13 |  6.25m |   3°   |  10%  |    no     |  no   |
| LV-T30 "Reliant"          |    240 |   310/265 |        1.25 |  1.25m |   -    |   -   |    no     |   7   |
| LV-T45 "Swivel"           |    215 |   320/250 |         1.5 |  1.25m |   3°   |   -   |    no     |   6   |
| S3 KS-25 "Vector"         |   1000 |   315/295 |         4.0 |  1.25m |   -    |   -   |    no     |   3   |
| RE-L10 "Poodle"           |    250 |    350/90 |        1.75 |  2.50m |   5°   |  30%  |    no     |   8   |
| RE-I5 "Skipper"           |    650 |   320/280 |         3.0 |  1.25m |   2°   |   -   |    no     |  10   |
| RE-M3 "Mainsail"          |   1500 |   310/285 |         6.0 |  2.50m |   2°   |   -   |    no     |  12   |
| KR-2L+ "Rhino"            |   2000 |   240/245 |         9.0 |  3.75m |   4°   |   -   |    no     |  12   |
| S3 KS-25x4 "Mammoth       |   4000 |   315/295 |        15.0 |  3.75m |   2°   |   -   |    no     |  12   |
| ***Making History***      |  ----- |  -------- |       ----- |   ---- |  ----  |  ---  |  -------  |  --   |
| Kerbodyne KE-1 "Mastodon" |   1350 |   305/290 |         5.0 | 1.875m |   5°   |  20%  |    no     |   8   |
| LV-T91 "Cheetah"          |   1000 |   355/150 |         1.0 | 1.875m |   4°   |  20%  |    no     |   5   |
| LV-TX87 "Bobcat"          |    400 |   310/290 |         2.0 | 1.875m |   5°   |  15%  |    no     |   8   |
| RE-I2 "Skiff"             |    300 |   315/295 |         1.6 |  2.50m |   2°   |  20%  |    no     |   3   |
| RE-J10 "Wolfhound"        |    375 |    380/70 |         3.3 |  2.50m |   3°   |   -   |    no     |   8   |
| RK-7 "Kodiak"             |    260 |   300/285 |        1.25 | 1.875m |   -    |   -   |    no     |   5   |
| ***Elephant Engine***     |  ----- |  -------- |       ----- |   ---- |  ----  |  ---  |  -------  |  --   |
| S3 KS-25x3 "Elephant"     |   3000 |   315/295 | 11.6255[^1] |  1.25m | 10.5°  |  8%   |  Yes[^2]  |   9   |

* excluded engines like
  * *LFB KR-1x2 "Twin-Boar" because over 25% is fuel tank and contents*
  * *RV-1 "Cub" because is radial attached or vernier or non-traditonal like aerospike*

* Mass Calculation:
  * Part I: (4 x 3) * (( 0.9375 + 1)/2) = 11.625.
  * Note: Averaged the ratio of 15:16 with 16:16 (or 1:1) for a nicer feeling number.
  * Explanation of math
    * 4 = Mass of Vector
    * 3 = Number of Vectors
    * 0.9375 = Mass of the Mammoth (15) / Mass of Four Vectors (16)

[^1]: this is already changed internally for next release  
[^2]: the "Elephant" engines multimode is purely gfx/sfx and does not affect game mechanics
