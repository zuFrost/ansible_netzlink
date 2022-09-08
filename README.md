### List of ansible technology
#### 1)	Inventory file
[ansible.cfg](https://github.com/zuFrost/ansible_netzlink/blob/main/ansible.cfg)
#### 2)	Hosts file with groups
[hosts.txt](https://github.com/zuFrost/ansible_netzlink/blob/main/hosts.txt)
#### 3)	Variables. Debug. Shell.
[playbook_vars.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook_vars.yml)
#### 4)	Group_variables with key pars in hierarchy
group_vars/
      ├── All_LINUX
      ├── STAGING_SERVERS_DB
        └── STAGING_SERVERS_WEB
#### 5)	Loops.
[playbook4_loop.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook4_loop.yml)
#### 6)	Roles
roles
└── deploy_apache_web
    ├── defaults
    │   └── [main.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/roles/deploy_apache_web/defaults/main.yml)
    ├── files
    │       └──  #=== WebSiteHierarchy===#
    ├── handlers
    │   └── [main.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/roles/deploy_apache_web/handlers/main.yml)
    ├── tasks
    │   └── [main.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/roles/deploy_apache_web/tasks/main.yml)
    ├── templates
    │   └── [index.j2](https://github.com/zuFrost/ansible_netzlink/blob/main/roles/deploy_apache_web/tasks/main.yml)
    └── vars
        └── [main.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/roles/deploy_apache_web/vars/main.yml)
#### 7)	Blocks and Conditionals. Handlers. Variables. Jinja Template. Roles.
Install Apache and upload Web Page on different RedHat and Debian systems
[playbook8_roles.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook8_roles.yml)
#### 8)	External variables.
[playbook9_external_var.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook9_external_var.yml)
#### 9)	Import. Include.
[playbook10_include.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook10_include.yml)
#### 10)	Delegate tasks.
[playbook11_delegate.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook11_delegate.yml)
#### 11)	Error handling.
[playbook12_error_handling.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook12_error_handling.yml)
#### 12)	Vault.
[playbook13_vault.yml](https://github.com/zuFrost/ansible_netzlink/blob/main/playbook13_vault.yml)
[mypass.txt](https://github.com/zuFrost/ansible_netzlink/blob/main/mypass.txt)
