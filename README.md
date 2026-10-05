# WoW Forever Paladin Gameplay Sim

A browser sim for practising level 60 Retribution and Shockadin Paladin rotations in World of Warcraft: Forever. You press the abilities; the sim auto-attacks a raid boss dummy, tracks mana, seals and cooldowns, and shows a damage breakdown when the dummy dies.

**Play it:** https://wowf-gameplay.github.io/paladin-gameplay-sim/

## Features

- Two specs on one page: Retribution (seal twisting with Seal of Command and Seal of Righteousness) and Shockadin (Holy Shock, Divine Favor)
- Judgement, Holy Strike, Consecration, Hammer of Wrath, Major Mana Potion and Demonic Rune
- Mana returns from Sanctified Judgement, Judgement of Wisdom and Blessing of Wisdom; Vengeance, Twist of Light Echoes, Crusader and Windfury procs
- Toggles for raid buffs, consumables and boss debuffs
- Gear and talent tabs, plus a Stats tab for entering your own character stats
- Rebindable keys (with Shift/Ctrl), adjustable dummy health, and a Warcraft Logs-style end-of-fight breakdown

## Setup

The default gear, enchants and talent builds follow the [MythicSim](https://mythicsim.com/wow-forever/tier-list) Retribution Paladin and Shockadin presets. Mechanics follow the open-source engine MythicSim is built on and Forever beta tooltips; a few values are fitted to MythicSim's results, and everything may change as the beta does.

## Running locally

It is a single file with no build step: open `index.html` in a browser. Ability icons load from Wowhead's image server, so they need an internet connection.

## Related

- [Warrior gameplay sim](https://github.com/wowf-gameplay/warrior-gameplay-sim)

## Disclaimer

Fan project, not affiliated with Blizzard Entertainment. World of Warcraft is a trademark of Blizzard Entertainment, Inc.
