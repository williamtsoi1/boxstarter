William's Boxstarter script
=========

The purpose of this repository is to store and share my boxstarter build so that whenever I have to reformat my computer I will have the machine built just the way I like it.

Installation
------------

- Install Chocolatey
```sh
@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```
- (optional) Fork this repo and make your own changes to boxstarter.txt as you desire
- Open up Internet Explorer, and browse to this URL
```
http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/williamtsoi1/boxstarter/master/boxstarter-desktop.txt
```
- If you made your own modifications to the script, change the querystring to suit
- Go to sleep for the night

More information
----------------
- Boxstarter - http://boxstarter.org
- Chocolatey - http://chocolatey.org
