# Third-party notices

The MIT license in [`LICENSE`](LICENSE) covers the Artemis+ team's own code and assets. The components below are in this repository under their own licenses and are **not** covered by the MIT grant.

## Kept in the repository

| Component | Path | License |
|---|---|---|
| Noto Color Emoji (Google) | `unity_codebase/Assets/External Assets/Noto Color Emoji/` | SIL Open Font License 1.1. See `LICENSE.txt`, `OFL.txt` and `COPYRIGHT.txt` in that folder. |
| Unity Starter Assets (First Person and Third Person Character Controllers) | `unity_codebase/Assets/StarterAssets/` | Unity Companion License. See `license.txt` in that folder and https://unity3d.com/legal/licenses/Unity_Companion_License |
| TextMesh Pro (Unity) | `unity_codebase/Assets/TextMesh Pro/` | Unity Companion License. The bundled Liberation Sans font is under the SIL Open Font License (`Fonts/LiberationSans - OFL.txt`). |

## Origin not yet confirmed

These folders were committed with the Unity project, and it is not yet confirmed that the team created them. Until confirmed, treat them as excluded from the MIT grant.

| Path | Note |
|---|---|
| `unity_codebase/Assets/Models/lunar-rover-from-the-movie-moon/` | The model file is named `lunar sketchfab.fbx`, which suggests a Sketchfab download. Author and license unknown. |
| `unity_codebase/Assets/Models/solar-panel/` | Same `source/` and `textures/` layout as a Sketchfab download. Author and license unknown. |

## Removed from the repository

Unity Asset Store packages used by the project are no longer committed. They must be bought or imported separately; see "Third-party assets (buy or import separately)" in [`README.md`](README.md). The compiled WebGL build in `backend/public/Build/` was produced with those packages installed.
