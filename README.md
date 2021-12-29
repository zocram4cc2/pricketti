# pricketti
## Gameplay patch for Pro Evolution Soccer 2019's VGL branch

Pricketti is the gameplay patch developed for the [/vg/League](https://implyingrigged.info/wiki//vg/_League) for its use in PES2019. This is achieved like the previous PES2021 patch by changing the binary constants file Konami left in the game's data packs. Its name is a portmanteu of the other patch's name and player #19 of the last /vg/L winner, /hgg2d/. Only the modified objects are included in the repository.

**Current patch notes:**
- Zeroed a bunch of wait times and animation delays
- Disabled all slow downs
- Enabled all [subConcepts](https://implyingrigged.info/wiki/User:MarcoZ/dt18_Files_Breakdown#Team)
- Tweaked the GK to rush out and punch slightly more rather than catch
- Spiked up first time chances (headers, volleys, etc.)
- Enhanced AI vision on long\wide chances for better wing play (both on the ground and in the air)
- Heightened stamina loss
- Heightened sliding range\speeds for more fouls
- Tweaked AI free kicks (more range of kick force)
- Various minor cursored player fixes (enabling a block animation, heightening the shoot ranges)
- Slightly diminished striker accuracy on non-first time chances


### How do I read this shit again?
The text files follow this format:
```bash
STOCK VALUE   PATCHED VALUE //variable description
```
