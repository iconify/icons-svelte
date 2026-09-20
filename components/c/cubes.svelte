<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/s/sd5y_0n2e.css';
import '../../css/g/gqtvblinr.css';
import '../../css/z/zhb7fx7pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="sd5y_0n2e"/><path class="gqtvblinr"/><path class="zhb7fx7pa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:cubes" {...props}></Icon>
