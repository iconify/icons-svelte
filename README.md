# @iconify-svelte/ion

**IonIcons**

Author: [Ben Sperry](https://github.com/ionic-team/ionicons)

License: [MIT](https://github.com/ionic-team/ionicons/blob/main/LICENSE)

Browse all icons: [preview IonIcons on Iconify](https://icon-sets.iconify.design/ion/)

## Installation

```bash
npm install github:iconify/icons-svelte#ion
```

## Usage

For full documentation visit [Iconify website](https://iconify.design/docs/usage/svg-css/svelte/).

Few usage examples:

```svelte
<script lang="ts">
import SampleIcon from '@iconify-svelte/ion/code-download-sharp';
</script>

<SampleIcon />
```

To resize icon, set `width` and/or `height` parameters:

```svelte
<script lang="ts">
import SampleIcon from '@iconify-svelte/ion/contrast-outline';
</script>

<SampleIcon height="1em" />
```

To change icon color, use style:

```svelte
<script lang="ts">
import SampleIcon from '@iconify-svelte/ion/checkmark-done';
</script>

<SampleIcon style="color: red;" />
```
