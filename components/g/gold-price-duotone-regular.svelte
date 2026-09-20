<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x60be2bhk"/><path class="u1klnyb3u"/><path class="rwt37ub5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gold-price-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rwt37ub5x) {
  d: path("m5 9.5 4 -4 3 3L18.5 2");
}

:global(.u1klnyb3u) {
  d: path("m2 18.5 5 -5h10l5 5Z");
}

:global(.x60be2bhk) {
  fill: currentColor;
  d: path("m2 18.5 5 -5h10l5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
