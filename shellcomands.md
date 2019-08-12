## shell commands

### .profile file
`.profile` file is a hidden file which tells the system which commands to run when 
the user whose profile file it is logs in. The contents of a `/Users/<user>/<user>.profile` 
file are executed on every log-in of the <user>.

`.bash_profile` is exactly the same. OS X looks for `etc/profile`, then for `~/.bash_profile`, 
`~/.bash_login` and finally `~/.profile`, and loads the first one of these it finds.

You can use any of them and rename/merge them into one - just keep in mind only the first one is
loaded.

**add alias**

```alias <name>="<command>"```

**re-loaded the file**

```source ~/.profile``` or ```. ~/.profile```
