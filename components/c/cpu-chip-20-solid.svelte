<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dff9ol9go.css';
import '../../css/g/g_xe81d2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="dff9ol9go"/><path clip-rule="evenodd" class="g_xe81d2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cpu-chip-20-solid" {...props}></Icon>
