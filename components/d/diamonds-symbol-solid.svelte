<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2bg46x2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a2bg46x2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:diamonds-symbol-solid" {...props}></Icon>
