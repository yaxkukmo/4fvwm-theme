# 4fvwm-theme

A personal FVWM window manager configuration inspired by the classic SGI IRIX 4Dwm look and feel. This config is almost 20 years old and has been refined over the years to keep the retro SGI aesthetic alive on modern Linux systems.

## Features

- SGI IRIX-style color scheme and window decorations
- Toolchest panel mimicking the original 4Dwm toolbar
- Red cursor theme
- Custom vector button styles for window title bar
- Icon management with automatic placement
- Sound events via `aplay`
- Multiple virtual desktops (Home, Work)
- FvwmPager for desktop overview
- Key bindings for volume, brightness, screenshots, and desktop locking
- XDG application menu integration

## Requirements

- FVWM 2.x
- `urxvt` — terminal emulator
- `7aclock` — analog clock
- `trayer` — system tray
- `aplay` — sound playback (part of `alsa-utils`)
- `pactl` — PulseAudio control (for volume keys)
- `xbacklight` — brightness control
- `scrot` — screenshots
- `xlock` — screen lock
- `nvim` — config file editing (via Toolchest menu)

## Installation

```sh
cp fvwmrc ~/.fvwm/fvwmrc
```

Make sure the icon and sound files are in place:

```
~/.fvwm/icons/
~/.fvwm/sounds/
~/.fvwm/sgi_logo.xpm
```

Then start FVWM with:

```sh
fvwm -f ~/.fvwm/fvwmrc
```

## Author

Yaxkukmo
