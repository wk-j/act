## Act

```bash
brew install act

act -l
act -j build
```

## Skip job

```yaml
- name: Upload 1
  if: ${{ !env.ACT }}
```