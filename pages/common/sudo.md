# sudo

> Executes a single command as another user.

- List the contents of an unreadable directory:

`sudo {{ls}} {{/usr/local/scrt}}`

- Edit a file as the user www:

`sudo -u {{www}} {{vi}} {{/var/www/index.html}}`

- Shut down the machine:

`sudo {{shutdown}} -h +10 {{"Cya soon!"}}`

- Repeat the last command as sudo:

`sudo !!`

- Launch the default shell with root privileges:

`sudo -i`

- Launch the default shell with root privileges but keeps the enviroment for the current user executing the command

`sudo -s`
