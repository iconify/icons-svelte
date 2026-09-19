<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei-fevb0d.css';
import '../../css/g/gefsnvbmp.css';
import '../../css/q/qx32elbez.css';
import '../../css/d/dlkwv-bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="ei-fevb0d"/><path class="gefsnvbmp"/><path class="mr-st1 qx32elbez"/><path class="dlkwv-bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mr-4x3" {...props}></Icon>
