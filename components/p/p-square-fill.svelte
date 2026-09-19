<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pnfujubwi.css';
import '../../css/f/fl9z2lbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pnfujubwi"/><path class="fl9z2lbeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:p-square-fill" {...props}></Icon>
