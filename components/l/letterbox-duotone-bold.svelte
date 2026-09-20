<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nk1mt_brr"/><path class="ra07l749q"/><path class="zawirs49s"/><path class="itq_ntb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:letterbox-duotone-bold" {...props}></Icon>
<style>
:global(.itq_ntb3g) {
  d: path("M11 16v5");
}

:global(.nk1mt_brr) {
  fill: currentColor;
  d: path("M5 16v-6a6 6 0 0 1 12 0v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ra07l749q) {
  d: path("M5 16v-6a6 6 0 0 1 12 0v6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zawirs49s) {
  d: path("M8 11h6");
}

</style>
