<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/e/ey92g6b7j.css';
import '../../css/k/k23tj10xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="pr52f_b5y"><path class="ey92g6b7j"/><path class="k23tj10xr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:hash-print" {...props}></Icon>
