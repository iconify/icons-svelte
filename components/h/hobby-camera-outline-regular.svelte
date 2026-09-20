<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vjzgivlgt"/><path class="jl4j86b7j"/><path class="iltwr9b-o"/><path class="y9mk1r17g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hobby-camera-outline-regular" {...props}></Icon>
<style>
:global(.iltwr9b-o) {
  d: path("M8 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.jl4j86b7j) {
  d: path("m8 8 3 -3h3l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vjzgivlgt) {
  d: path("M3 8v11h18V8Z");
}

:global(.y9mk1r17g) {
  d: path("M17 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
