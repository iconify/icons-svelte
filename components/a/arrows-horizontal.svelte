<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oybjd3s2z.css';
import '../../css/t/turgpe-dg.css';
import '../../css/c/ccvr2ibtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oybjd3s2z"/><path class="turgpe-dg"/><path class="ccvr2ibtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrows-horizontal" {...props}></Icon>
