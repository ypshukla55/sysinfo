# sysinfo
Ansible playbook which gathers multiple information from given list of hosts, including service status, make sure if defined services are running if not, restart the services, show disk usage, check logs, etc and generates a html report.

Before executing the playbook, make sure you have set the secret variable if your user doesn't have access to passwordless sudo.

Simply run the command

#ansible-playbook -i hosts info.yml