<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k0u_xl_dw"/><path class="h3siy4w6z"/><path class="sgr_j7bvk"/><path class="yazo7scbq"/><path class="fmlaifbpn"/><path class="ffwaozrbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:injection-duotone-regular" {...props}></Icon>
<style>
:global(.ffwaozrbk) {
  d: path("M10 10h4");
}

:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.h3siy4w6z) {
  d: path("M8 8a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.k0u_xl_dw) {
  fill: currentColor;
  d: path("M8 8a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
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

:global(.sgr_j7bvk) {
  d: path("M8 3h8");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
