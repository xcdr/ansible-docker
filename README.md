# Ansible role for Docker

This is a simple Ansible role for installing Docker via ansible-galaxy.

The role should work on all Debian based distributions.

## Installation

Add this to your `requirements.yml`:

```yml
- src: https://github.com/xcdr/ansible-docker
  name: xcdr.docker
```

## Example playbook

```yaml
---

- hosts: myhost
  roles: xcdr.docker
```

## License

MIT
