<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/axm7mdb8n.css';
import '../../css/u/uxddagbff.css';
import '../../css/p/p-tl4pbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="axm7mdb8n"/><path class="uxddagbff"/><path class="p-tl4pbfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-graph-outline" {...props}></Icon>
