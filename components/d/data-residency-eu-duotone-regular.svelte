<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xa771-t-o"/><path class="o89tku_be"/><path class="gb7_c5bdk"/><path class="o1bec9b2h"/><path class="wa5ty6w9r"/><path class="ugdbidcqi"/><path class="ajxlkdb4q"/><path class="sqmmri1vo"/><path class="da_3coiun"/><path class="vz97hm34i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-residency-eu-duotone-regular" {...props}></Icon>
<style>
:global(.ajxlkdb4q) {
  d: path("M11 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.da_3coiun) {
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gb7_c5bdk) {
  fill: currentColor;
  d: path("M15.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.o1bec9b2h) {
  fill: currentColor;
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o89tku_be) {
  fill: currentColor;
  d: path("M11 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sqmmri1vo) {
  d: path("M15.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

:global(.vz97hm34i) {
  d: path("M6.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wa5ty6w9r) {
  fill: currentColor;
  d: path("M6.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xa771-t-o) {
  fill: currentColor;
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
