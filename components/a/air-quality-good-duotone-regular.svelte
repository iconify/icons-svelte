<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emyboub8n"/><path class="tbe304aqf"/><path class="pb3e3w72c"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="phq59z-bc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-quality-good-duotone-regular" {...props}></Icon>
<style>
:global(.emyboub8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pb3e3w72c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 11 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.phq59z-bc) {
  d: path("m8 11 3 3 5 -5");
}

:global(.tbe304aqf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
