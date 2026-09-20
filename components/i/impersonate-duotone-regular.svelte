<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qhdq2dbof"/><path class="n8oxfwbbl"/><path class="ejfmpibyt"/><path class="zdn0azbfs"/><path class="bt921xbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:impersonate-duotone-regular" {...props}></Icon>
<style>
:global(.bt921xbxy) {
  d: path("M5 21a7 7 0 0 1 14 0");
}

:global(.ejfmpibyt) {
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.n8oxfwbbl) {
  fill: currentColor;
  d: path("M11 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

:global(.qhdq2dbof) {
  fill: currentColor;
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zdn0azbfs) {
  d: path("M11 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
