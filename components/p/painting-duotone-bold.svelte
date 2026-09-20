<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rb8ofhiko"/><path class="zugrfydpd"/><path class="x7x2dubhn"/><path class="yl6rclbxh"/><path class="bvxg1_b9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:painting-duotone-bold" {...props}></Icon>
<style>
:global(.bvxg1_b9x) {
  d: path("m18 6 4 4 -2 2 -4 -4Z");
}

:global(.rb8ofhiko) {
  fill: currentColor;
  d: path("M3 4v12h12V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x7x2dubhn) {
  d: path("M3 4v12h12V4Z");
}

:global(.yl6rclbxh) {
  d: path("m13 15 7 -7");
}

:global(.zugrfydpd) {
  fill: currentColor;
  d: path("m18 6 4 4 -2 2 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
