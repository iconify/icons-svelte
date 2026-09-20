<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="otxscghkz"/><path class="gwl0nvbom"/><path class="x7gsyjbtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reserved-discount-outline-regular" {...props}></Icon>
<style>
:global(.gwl0nvbom) {
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.otxscghkz) {
  d: path("M3 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.x7gsyjbtr) {
  d: path("M14 13h5l2.5 2.5L19 18h-5Z");
}

</style>
