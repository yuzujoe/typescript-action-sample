<p align="center">
  <a href="https://github.com/actions/typescript-action/actions"><img alt="typescript-action status" src="https://github.com/actions/typescript-action/workflows/build-test/badge.svg"></a>
</p>

# PR Comment Action

This action comments a message on PR.

## Inputs

### `repo-token`

**Required** The message to comment on PR.

## Outputs

### `commentUrl`

The PR comment URL.

## Example Usage

```yaml
uses: github-actions-up-and-running/pr-comment@v1.0.0
with:
    repo-token: ${{ secrets.GITHUB_TOKEN }}
    message: Nice PR!
```
