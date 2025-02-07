# Cursor-install-linux
## install
```bash
git clone https://github.com/yukino0832/Cursor-install-linux.git && cd Cursor-install-linux
chmod +x install_cursor.sh
./install_cursor.sh
```
## uninstall
```bash
sudo rm -f /opt/cursor.appimage /opt/cursor.png /usr/share/applications/cursor.desktop
sed -i '/# Cursor alias/,+3d' ~/.bashrc
exec bash
```