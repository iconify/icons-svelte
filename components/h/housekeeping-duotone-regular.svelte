<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e0ztlokmq"/><path class="k3yb39bcy"/><path class="qvcijezyh"/><path class="o41x62nfc"/><path class="sxlwlmkmh"/><path class="t56w4f31r"/><path class="zbeuuub3n"/><path class="z4g4wjbvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:housekeeping-duotone-regular" {...props}></Icon>
<style>
:global(.e0ztlokmq) {
  fill: currentColor;
  d: path("M4 6v12h16V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k3yb39bcy) {
  fill: currentColor;
  d: path("M6 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.o41x62nfc) {
  d: path("M4 6v12h16V6Z");
}

:global(.qvcijezyh) {
  fill: currentColor;
  d: path("M16 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.t56w4f31r) {
  d: path("M6 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.z4g4wjbvf) {
  d: path("M6 3h6");
}

:global(.zbeuuub3n) {
  d: path("M16 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
