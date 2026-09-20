<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ots31sbwo"/><path class="m1o3_obxt"/><path class="jd_dotbnq"/><path class="h2fnwccfy"/><path class="qvytntb8g"/><path class="pyijoo9dk"/><path class="xaev2ybax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:live-tail-duotone-regular" {...props}></Icon>
<style>
:global(.h2fnwccfy) {
  d: path("M7 6h10");
}

:global(.jd_dotbnq) {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

:global(.m1o3_obxt) {
  fill: currentColor;
  d: path("M13 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.ots31sbwo) {
  fill: currentColor;
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pyijoo9dk) {
  d: path("M7 14h3");
}

:global(.qvytntb8g) {
  d: path("M7 10h10");
}

:global(.xaev2ybax) {
  d: path("M13 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
