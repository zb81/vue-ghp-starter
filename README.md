# About this repo

A GitHub Page template, based on Vue3 + Vite.

Before the start, you need to create a empty repo and add `Repository secrets` named `ACCESS_TOKEN`.

> [About Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets#about-encrypted-secrets)
>
> [About Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#about-personal-access-tokens)

## 1. Clone repo

```bash
npm install -g degit

cd /path/to/your/project-name

degit https://github.com/zb81/vue3-ghp-starter
```

## 2. Globally replace `vue3-ghp-starter` with your own `project_name`

- `package.json`
- `vite.config.ts`

## 3. Develop and deploy

Preview your website in https://your-username.github.io/project-name.
