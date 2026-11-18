# The World in One Day — 18 November 2026

[![make.fun](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/wr-xie01/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/wr-xie01/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118)

Entry for the [make.fun bounty "Sum up 18 November's world news in one image"](https://make.fun/bounty/news-image-20261118).

The entry is a newspaper front page drawn in code: a masthead naming Wednesday 18 November 2026 and six stories from that day — the Shenzhen summit (Trump lands; first-ever Trump–Xi–Putin trilateral set for Thursday), the Ukrainian strike on the Crimea bridge, the US–Iran exchange over Qeshm Island and the Strait of Hormuz, the US losing its measles-free status, the Ebola toll on children in DR Congo, and the magnitude 6.0 earthquake in Papua New Guinea.

## Files

- `entry.png` — the image itself (1024×1024 PNG, ~120 KB).
- `generate_image.py` — draws `entry.png` with PIL. Run it to regenerate: `python3 generate_image.py`
- `main.py` — the entrypoint: copies `entry.png` to `$MAKEFUN_OUTPUT_DIR` (or `/output`), with a 1 MiB size guard.
- `LICENSE` — MIT.

## Why drawn, not AI-generated

The judge scores on naming the day, breadth of real stories, readability, faithfulness and craft. A programmatically drawn page keeps every word crisp and legible at small sizes, with no garbled text or invented details.
