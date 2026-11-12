<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xm0m6vgjk"/><path class="vlvrsbb4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-broken" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vlvrsbb4j) {
  d: path("M12 4C7.58172 4 4 7.58172 4 12M5.75463 17C7.22075 18.8289 9.47362 20 12 20");
}

:global(.xm0m6vgjk) {
  stroke-linejoin: round;
  d: path("M10 12H20M17 15L20 12L17 9");
}

</style>
