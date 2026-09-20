<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ps-_1ne9q"/><path class="s_yfbmb1g"/><path class="krpni0u_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-rank-outline-bold" {...props}></Icon>
<style>
:global(.krpni0u_o) {
  d: path("m7 22 5 -5 5 5");
}

:global(.ps-_1ne9q) {
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
}

:global(.s_yfbmb1g) {
  d: path("m7 17.5 5 -5 5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
