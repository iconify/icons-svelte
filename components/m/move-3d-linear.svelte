<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qim-6bkwl.css';
import '../../css/q/qlvg9o9nq.css';
import '../../css/m/mcf4dis3x.css';
import '../../css/l/l_z-b8vui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qim-6bkwl"/><path class="qlvg9o9nq"/><path class="mcf4dis3x"/><path class="l_z-b8vui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-3d-linear" {...props}></Icon>
