<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p-6v8o44a"/><path class="j9mpubb9t"/><path class="l0q87g1mm"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dew-point-duotone-bold" {...props}></Icon>
<style>
:global(.j9mpubb9t) {
  d: path("m12 6 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.l0q87g1mm) {
  d: path("M20 14a8 8 0 0 1 -16 0");
}

:global(.p-6v8o44a) {
  fill: currentColor;
  d: path("m12 6 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
