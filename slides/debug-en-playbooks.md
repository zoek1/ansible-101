##  Debug en playbooks

El modulo debug puede ser de gran ayuda!

```yml
- name:  Verificar un valor
  debug: msg={{ ansible_distribution }}
```
