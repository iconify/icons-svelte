<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s2r04acoo"/><path class="ahq5brb1v"/><path class="q518x4bkb"/><path class="gcalxb98a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:element-duotone-regular" {...props}></Icon>
<style>
:global(.ahq5brb1v) {
  d: path("M5 4h14v14H5Z");
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q518x4bkb) {
  d: path("M5 9h14");
}

:global(.s2r04acoo) {
  fill: currentColor;
  d: path("M5 4h14v14H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
