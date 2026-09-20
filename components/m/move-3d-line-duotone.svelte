<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qim-6bkwl.css';
import '../../css/q/qlvg9o9nq.css';
import '../../css/m/mcf4dis3x.css';
import '../../css/a/at5_xs54h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qim-6bkwl"/><path class="qlvg9o9nq"/><path class="mcf4dis3x"/><path class="at5_xs54h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-3d-line-duotone" {...props}></Icon>
