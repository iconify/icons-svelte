<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w_snsacfd"/><path class="gswswg2-b"/><path class="hv3ppsbji"/><path class="korq7_l8k"/><path class="m-p3hbclp"/><path class="hc7fbd-jo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:navbar-outline-bold" {...props}></Icon>
<style>
:global(.gswswg2-b) {
  d: path("M5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hc7fbd-jo) {
  d: path("M4 19h16");
}

:global(.hv3ppsbji) {
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.korq7_l8k) {
  d: path("M17 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w_snsacfd) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
