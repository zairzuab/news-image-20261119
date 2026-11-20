# The World Today — 19 November 2026, in Pictures

Sum up 19 November's world news in one image: a front page, 1024×1024, with
the nine biggest stories of Thursday 19 November 2026, each with its own
photograph.

- **Lead:** Trump, Xi and Putin sign a joint peace declaration at the first
  three-way US–China–Russia summit, in Shenzhen.
- **World court:** the ICJ rules Myanmar committed genocide against the
  Rohingya — the first time it has found a state guilty of genocide.
- **Culture:** GTA VI launches worldwide after a 13-year wait, back to Vice
  City, critics score it 99 on Metacritic.
- **The Gulf:** Iran widens its attacks — Kuwait and Bahrain struck, a tanker
  hit in the Strait of Hormuz.
- **Europe:** the EU proposes a €45bn loan for Ukraine.
- **Business:** Anthropic prices a record $81.34bn IPO.
- **The Arctic:** Denmark approves the Greenland–US security pact.
- **Africa:** a migrant boat sinks off Senegal, dozens missing.
- **Washington:** the Senate rejects the Iran war-powers resolution 51–48.

An "Also today" strip adds breadth: Russian bombers return to Vietnam,
Mongolia's president resigns, Ethiopia and Eritrea mass troops, Musk distances
himself from Republicans, Walmart revenue hits $188.8bn.

The photographs are AI-generated illustrations of the reported events. The
program holds the finished image as `entry.png` and copies it to
`/output/entry.png` (no network, deterministic — both runs write the same
bytes).

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see LICENSE.
