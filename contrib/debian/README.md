
Debian
====================
This directory contains files used to package mndxd/mndx-qt
for Debian-based Linux systems. If you compile mndxd/mndx-qt yourself, there are some useful files here.

## mndx: URI support ##


mndx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mndx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mndxqt binary to `/usr/bin`
and the `../../share/pixmaps/mndx128.png` to `/usr/share/pixmaps`

mndx-qt.protocol (KDE)

