<img width="2694" height="606" alt="image" src="https://github.com/user-attachments/assets/b386a93b-46aa-4ef7-b07f-50b0162fc77f" />

# -=BetterRCS_KSP=-
Better looking Waterfall FX for KSP's RCS thrusters.

For a long time I've been dissatisfied with KSP's RCS thrusters, only really using BDB's because they had the longer plumes that actual RCS thrusters have. The release of a playable build of KSA, and the RCS effects in that game in general, spurred me to actually do something about the problem. BetterRCS is what came of that, replacing every RCS thruster plume in the game (including all modded thrusters) to come closer to reality.

I need to thank WarriorSabe on the Kerbal Community discord server, as they essentially gave me a crash course in the dark arts of ModuleManager. Without them, this mod wouldn't have been possible in the way that it is now.


# -=Known Issues=-

*In order for thrusters to be compatible, they must already have a waterfall configuration.*

*Parts with multiple ModuleRCSFX modules likely won't have different plume templates, this is due to a limitation in what is possible with a modulemanager patch.*

*Some thrusters are known to have incorrect plume placement, this includes some Restock RCS thrusters, **please report any issues found with placement and include the specific mod and part so that I can reproduce the problem.***

# -=Changelog=-

**v0.1.7 - 2/26/2026**

-Aesthetic update to plumes to make the atmospheric effects a bit less awful.


**v0.1.6 - 2/12/2026**

-Made the Regex patch now properly modify parts with multiple ModuleRCSFX


**v0.1.5 - 12/29/2025**

-Made the template replacement consider whether or not the template to replace uses an RCS controller.

-Honestly that was a massive oversight.


**v0.1.4 - 12/25/2025**

-Updated BetterRCS_Base to look better.

-Refined support for InternalRCS.


**v0.1.3 - 12/24/2025**

-Fixes for Tundra's RCS thrusters plus a couple stock and one iRCS thruster.


**v0.1.2 - 12/22/2025**

-Hotfix, Hydrolox and Methalox RCSShocks were erroneously angled 90 degrees and also didn't respond to thrust inputs.


**v0.1.1  - 12/22/2025**

-Added Hydrolox and Methalox plumes

-Updated ISP-based plumes to be more realistic and less goofy looking

-Specifically fixed BetterRCS_Base so the jelly effect isn't wildly expanded in vacuum


**v0.1.0 12/21/2025**

-Added Regex based separation of RCS thruster types based on ISP

-Added 4 basic plumes for each thruster type
