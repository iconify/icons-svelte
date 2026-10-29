<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/f3i48zlop.css';
import '../../css/v/vn7k32bvs.css';
import '../../css/w/wt6q7nbgv.css';
import '../../css/q/quy7-c9io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="f3i48zlop wm-deco"/><path class="vn7k32bvs wm-deco"/><path class="wt6q7nbgv"/><path class="quy7-c9io"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-blueprint" {...props}></Icon>
