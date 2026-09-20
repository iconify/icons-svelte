<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mwqpylb0b"/><path class="gvik8m1ti"/><path class="ab_clyzfw"/><path class="ulpw-dlmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-bed-duotone-regular" {...props}></Icon>
<style>
:global(.ab_clyzfw) {
  d: path("M3 14c0 -4 4 -6 9 -6s9 2 9 6c0 3 -4 4 -9 4s-9 -1 -9 -4");
}

:global(.gvik8m1ti) {
  fill: currentColor;
  d: path("M7 14c0 -2 2 -3 5 -3s5 1 5 3c0 1.5 -2 2 -5 2s-5 -0.5 -5 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mwqpylb0b) {
  fill: currentColor;
  d: path("M3 14c0 -4 4 -6 9 -6s9 2 9 6c0 3 -4 4 -9 4s-9 -1 -9 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ulpw-dlmu) {
  d: path("M7 14c0 -2 2 -3 5 -3s5 1 5 3c0 1.5 -2 2 -5 2s-5 -0.5 -5 -2");
}

</style>
