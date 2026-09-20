<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emyboub8n"/><path class="tbe304aqf"/><path class="qabs6ac_i"/><path class="tec0j4bqc"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="lmbhihbzq"/><path class="xmg9uv4ey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pressure-falling-duotone-regular" {...props}></Icon>
<style>
:global(.emyboub8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmbhihbzq) {
  d: path("m12 16 -5 -5");
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

:global(.qabs6ac_i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 16 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbe304aqf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tec0j4bqc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 11H7v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xmg9uv4ey) {
  d: path("M10.5 11H7v3.5");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
