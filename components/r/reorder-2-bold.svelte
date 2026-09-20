<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/swmj859dg.css';
import '../../css/c/cmyxzeb6m.css';
import '../../css/f/fgizidusj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="swmj859dg"/><path class="cmyxzeb6m"/><path class="fgizidusj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-2-bold" {...props}></Icon>
