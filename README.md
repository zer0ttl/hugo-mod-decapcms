# hugo-mod-decapcms

hugo-mod-decapcms is a Hugo module that integrates DecapCMS for you to use in your web projects.

The files for Decap CMS get mounted in `static/admin/`.

## Use

1. Import the module into your Hugo project's site config as follows:

- Toml

```toml
[[module.imports]]
path = "github.com/zer0ttl/hugo-mod-decapcms"
```

- YAML

```yaml
module:
  imports:
    - path: "github.com/zer0ttl/hugo-mod-decapcms"
```

2. You can then add your own `static/admin/config.yml` file to modify the config for Decap CMS.