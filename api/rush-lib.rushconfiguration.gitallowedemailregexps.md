[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RushConfiguration](./rush-lib.rushconfiguration.md) &gt; [gitAllowedEmailRegExps](./rush-lib.rushconfiguration.gitallowedemailregexps.md)

# RushConfiguration.gitAllowedEmailRegExps property

\[Part of the "gitPolicy" feature.\] A list of regular expressions describing allowable e-mail patterns for Git commits. They are case-insensitive anchored JavaScript RegExps. Example: ".\*@example\\.com" This array will never be undefined.

**Signature:**
```javascript
gitAllowedEmailRegExps: string[]
```