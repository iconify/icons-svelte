<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="js6t3bb6m"/><path class="q9dd829qf"/><path class="f0lu7bcgk"/><path class="mzz93ed1z"/><path class="y0y0ccsoe"/><path class="lmdddlr1e"/><path class="p7w3a5bcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:binoculars-duotone-regular" {...props}></Icon>
<style>
:global(.f0lu7bcgk) {
  d: path("M3 8v11h7V8Z");
}

:global(.js6t3bb6m) {
  fill: currentColor;
  d: path("M3 8v11h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lmdddlr1e) {
  d: path("M4 5h5");
}

:global(.mzz93ed1z) {
  d: path("M14 8v11h7V8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p7w3a5bcn) {
  d: path("M15 5h5");
}

:global(.q9dd829qf) {
  fill: currentColor;
  d: path("M14 8v11h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

</style>
