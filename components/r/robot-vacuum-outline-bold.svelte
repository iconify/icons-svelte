<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqda50bqs"/><path class="ayfcapvsy"/><path class="ki-5h0s5c"/><path class="t_-p3gl9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:robot-vacuum-outline-bold" {...props}></Icon>
<style>
:global(.ayfcapvsy) {
  d: path("M9 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.ki-5h0s5c) {
  d: path("M6 6h12");
}

:global(.nqda50bqs) {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t_-p3gl9a) {
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
