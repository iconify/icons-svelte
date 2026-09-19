<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xr0-4kb2q.css';
import '../../css/y/ypyppybok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="cuyn6tgcc"><path class="xr0-4kb2q"/><path class="ypyppybok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:copilot-large" {...props}></Icon>
