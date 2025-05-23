---
aliases: "Vault.rename"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`Vault`](Vault) › [`rename`](Vault/rename)

## Vault.rename() method

Rename or move a file. To ensure links are automatically renamed, use [FileManager.renameFile()](FileManager/renameFile) instead.

**Signature:**

```typescript
rename(file: TAbstractFile, newPath: string): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>file</code> | [`TAbstractFile`](TAbstractFile) | the file to rename/move |
|  <code>newPath</code> | <code>string</code> | vault absolute path to move file to. |

**Returns:**

`Promise<void>`

