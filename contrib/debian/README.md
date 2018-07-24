
Debian
====================
This directory contains files used to package wochaind/wochain-qt
for Debian-based Linux systems. If you compile wochaind/wochain-qt yourself, there are some useful files here.

## wochain: URI support ##


wochain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wochain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wochain-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

wochain-qt.protocol (KDE)

