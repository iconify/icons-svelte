<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fkoirnb0d"/><path class="oncki7f2g"/><path class="c6bhbubal"/><path class="y3g1wztdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coal-plant-outline-bold" {...props}></Icon>
<style>
:global(.c6bhbubal) {
  d: path("M7.5 12a2.5 2.5 0 0 1 0 -5");
}

:global(.fkoirnb0d) {
  d: path("M5 20v-8h5v8Z");
}

:global(.oncki7f2g) {
  d: path("M13 20v-5h5v5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y3g1wztdf) {
  d: path("M7.5 2a2.5 2.5 0 0 1 0 5");
}

</style>
