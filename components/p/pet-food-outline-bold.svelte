<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v740ayb7w"/><path class="xejjxw8bt"/><path class="drftkjb-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-food-outline-bold" {...props}></Icon>
<style>
:global(.drftkjb-q) {
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v740ayb7w) {
  d: path("M7 7v14h10V7Z");
}

:global(.xejjxw8bt) {
  d: path("M7 7c0 -3 10 -3 10 0");
}

</style>
