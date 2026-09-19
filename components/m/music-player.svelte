<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ub0p2rb4l.css';
import '../../css/n/nd_emezuh.css';
import '../../css/q/qznqlw_ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ub0p2rb4l"/><path class="nd_emezuh"/><path class="qznqlw_ir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:music-player" {...props}></Icon>
