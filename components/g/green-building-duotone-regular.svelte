<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v207ltbrk"/><path class="o7lcglbcr"/><path class="k0bfs0wpz"/><path class="xmopbdc-t"/><path class="pbzp0rm9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:green-building-duotone-regular" {...props}></Icon>
<style>
:global(.k0bfs0wpz) {
  d: path("M5 21V10h14v11Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o7lcglbcr) {
  fill: currentColor;
  d: path("M8.5 9.5c0 -4.2 2.8 -7 7 -7 0 4.2 -2.8 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pbzp0rm9r) {
  d: path("M8.5 9.5c0 -4.2 2.8 -7 7 -7 0 4.2 -2.8 7 -7 7");
}

:global(.v207ltbrk) {
  fill: currentColor;
  d: path("M5 21V10h14v11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xmopbdc-t) {
  d: path("M5 15h14");
}

</style>
