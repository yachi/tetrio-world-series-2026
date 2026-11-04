# TETR.IO World Series 2026: round-by-round stats

Site: https://yachi.github.io/tetrio-world-series-2026/

Unofficial stats for 32 broadcast matches of the TETR.IO World Series 2026 (weeks 1 and 2), read from the
broadcast overlay. Every round winner was checked by hand against the on-screen board and score bar; small
reading errors in the numbers are possible.

- `index.html`: every match, with its set and round score and how many rounds have stats.
- `m/<video id>.html`: every round with a link to its moment in the video, the winner and, where readable,
  each player's VS, APP, PPS, APM, attack, pieces and round time.
- `players.html`: per-player totals over the event, beside the account's current TETR.IO League rating
  (TR, rank, standing, League APM/PPS/VS, read from ch.tetr.io on 2026-11-04).
- `teams.html`: match, set and round records over the matches on this site.
- `rounds.csv` and `data.json`: the raw data, one row per player per round.
- `txt/<video id>.txt`: the timestamp list for each video.

Definitions: APP = attack ÷ pieces; APM = 60 × attack ÷ round time. Where the round time was not read it is
estimated as pieces ÷ PPS and marked with `*` (`time_estimated` in the data). Some broadcasts show one
player's stats too faintly to read, so those matches list winners and timestamps only.
