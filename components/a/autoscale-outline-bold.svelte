<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cnllexbmp"/><path class="kvksesm4i"/><path class="fddkg0b5z"/><path class="jtvi3oeim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:autoscale-outline-bold" {...props}></Icon>
<style>
:global(.cnllexbmp) {
  d: path("M3 5a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.fddkg0b5z) {
  d: path("M19 7v10");
}

:global(.jtvi3oeim) {
  d: path("m16 10 3 -3 3 3");
}

:global(.kvksesm4i) {
  d: path("M3 15a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
