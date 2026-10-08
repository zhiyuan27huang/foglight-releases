## Install on Mac

**Requires a Mac with Apple Silicon (M1 or newer).** Intel Macs are not supported.
To check: Apple menu → About This Mac → "Chip" should say Apple M1/M2/M3/M4.

1. Go to the [latest release](https://github.com/zhiyuan27huang/foglight-releases/releases/latest) and download the file ending in `_aarch64.dmg` (about 180 MB).
2. Open the downloaded `.dmg` and drag **Foglight** into the **Applications** folder.
3. Open **Applications** and double-click **Foglight**. macOS will block it the first time, because Foglight is not yet registered with Apple. Click **Done** (not "Move to Trash").
4. Open **System Settings → Privacy & Security**, scroll down to **Security**, and click **Open Anyway** next to the Foglight message. Confirm with your password or Touch ID.
5. Foglight opens. You only need to do steps 3–4 once.

### If it still won't open

- **On macOS 14 or older:** in Applications, right-click **Foglight** → **Open** → **Open**.
- **If macOS says "Foglight is damaged and can't be opened":** the app is not damaged. Open **Terminal**, paste this line, press Return, then open Foglight again:

      xattr -cr /Applications/Foglight.app

### Updates

You only install once. Foglight downloads new versions by itself while it is open, and you get the new version the next time you open it.
