<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g4-0p1n1h"/><path class="j8hnr9b3j"/><path class="iqp9rd4vv"/><path class="pj9q08bqv"/><path class="vtk0-_bov"/><path class="pe31e6bgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pebble-duotone-regular" {...props}></Icon>
<style>
:global(.g4-0p1n1h) {
  fill: currentColor;
  d: path("M3 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iqp9rd4vv) {
  fill: currentColor;
  d: path("M7.5 17a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j8hnr9b3j) {
  fill: currentColor;
  d: path("M12.5 8a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
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

:global(.pe31e6bgt) {
  d: path("M7.5 17a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.pj9q08bqv) {
  d: path("M3 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.vtk0-_bov) {
  d: path("M12.5 8a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
