<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bd9evwuyg"/><path class="jof7c9fpk"/><path class="slranxf_s"/><path class="xyf3o9drf"/><path class="fl4996b6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-conditioner-outline-bold" {...props}></Icon>
<style>
:global(.bd9evwuyg) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.fl4996b6i) {
  d: path("M17 15v5");
}

:global(.jof7c9fpk) {
  d: path("M4 9h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.slranxf_s) {
  d: path("M7 15v5");
}

:global(.xyf3o9drf) {
  d: path("M12 15v5");
}

</style>
