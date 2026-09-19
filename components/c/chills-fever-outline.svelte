<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e_jyn858d.css';
import '../../css/r/rvp3pobsz.css';
import '../../css/z/z27jm6b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e_jyn858d"/><path class="rvp3pobsz"/><path clip-rule="evenodd" class="z27jm6b0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chills-fever-outline" {...props}></Icon>
