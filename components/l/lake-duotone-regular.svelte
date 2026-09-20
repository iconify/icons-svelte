<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mr9exyh3n"/><path class="nd-_isc6y"/><path class="rkhcgsbdl"/><path class="xn7bwccty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lake-duotone-regular" {...props}></Icon>
<style>
:global(.mr9exyh3n) {
  fill: currentColor;
  d: path("M4 12a8 5 0 1 0 16 0 8 5 0 1 0 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nd-_isc6y) {
  d: path("M4 12a8 5 0 1 0 16 0 8 5 0 1 0 -16 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.xn7bwccty) {
  d: path("M8 6h8");
}

</style>
