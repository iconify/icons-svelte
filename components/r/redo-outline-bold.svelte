<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r8sldsvbw"/><path class="ltbxi_2yl"/><path class="vru74db2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:redo-outline-bold" {...props}></Icon>
<style>
:global(.ltbxi_2yl) {
  d: path("M5 13v5");
}

:global(.r8sldsvbw) {
  d: path("M5 13a7 7 0 0 1 14 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vru74db2q) {
  d: path("m16 10 3 3 3 -3");
}

</style>
