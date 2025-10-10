
# 🖼️ error.os Neospace 2025 Wallpapers

A Debian package that installs the official **error.os Neospace 2025** wallpaper collection.  
Includes branded artwork and a curated set of solid color backgrounds.

---

## 📦 Install

### Step 1 — Download
Click here to download the installer:  
[⬇️ .deb installer](https://github.com/zynomon/errpaper/raw/main/errpaper.deb)

Or download via terminal:
```bash
wget https://github.com/zynomon/errpaper/raw/main/errpaper.deb -O errpaper.deb
```

### Step 2 — Install
You can install the package either by double‑clicking the `.deb` file (using GNOME Software, KDE Discover, Cosmic Store, or Synaptic),  
**or** from the terminal:

```bash
sudo apt install ./errpaper.deb
```

If you downloaded it to another directory, adjust the path accordingly (e.g. `~/Downloads/errpaper.deb`).

If you encounter dependency issues, fix them with:
```bash
sudo apt-get install -f
```

---

## 🎨 Usage

Wallpapers are installed to:

```
/usr/share/wallpapers/erroros/
```

The system default wallpaper symlink is managed at:

```
/usr/share/wallpapers/default
```

Switch wallpapers with:

```bash
sudo update-alternatives --config default-wallpaper
```

Point your desktop environment (GNOME, KDE, XFCE, etc.) to `/usr/share/wallpapers/default` once.  
From then on, changing the alternative will automatically update your background.

---

## ✨ Preview

*(Add thumbnails of your wallpapers here for a visual showcase)*

---

## 📝 License

- error.os wallpapers: Apache 2.0  
