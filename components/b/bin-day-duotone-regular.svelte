<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yg815lb3z"/><path class="mftdaepvv"/><path class="yo6r9h8xo"/><path class="ej_n65bgd"/><path class="pwvj2zbau"/><path class="n0k4ov7kr"/><path class="rso9r0bef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bin-day-duotone-regular" {...props}></Icon>
<style>
:global(.ej_n65bgd) {
  d: path("M6 8v11h10V8Z");
}

:global(.mftdaepvv) {
  fill: currentColor;
  d: path("M7 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0k4ov7kr) {
  d: path("M7 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pwvj2zbau) {
  d: path("M5 8V5h12v3");
}

:global(.rso9r0bef) {
  d: path("M13 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yg815lb3z) {
  fill: currentColor;
  d: path("M6 8v11h10V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yo6r9h8xo) {
  fill: currentColor;
  d: path("M13 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
