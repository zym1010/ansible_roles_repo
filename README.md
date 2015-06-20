# ansible_roles_repo
A collection of Ansible roles I use for maintenance.


`ansible.cfg` is a typical config file when using Ansible manually with Vagrant.

## playbooks

save some playbooks I used for configuring different environments. To actually use them, I guess you have to move them out of `playbooks` directory and make them have the same parent folder as the `roles` folder, as <https://docs.ansible.com/playbooks_roles.html#roles> suggests.

* `playbook_vr2014.yml` The one I used to configure the Vagrant machine for VR2014 paper (revised version, submitted in June 2015).

## roles 

simply all roles. For some roles, some files are omitted (`matlab`, for example), for obvious reason.