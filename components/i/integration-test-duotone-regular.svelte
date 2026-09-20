<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z640i9ymj"/><path class="t7edyg0pd"/><path class="b842d4b5v"/><path class="sgjb9gifn"/><path class="qot4e3zhe"/><path class="w9g5wtasy"/><path class="fkf_gcbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:integration-test-duotone-regular" {...props}></Icon>
<style>
:global(.b842d4b5v) {
  fill: currentColor;
  d: path("M14 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fkf_gcbra) {
  d: path("M10 15h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qot4e3zhe) {
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.sgjb9gifn) {
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3Z");
}

:global(.t7edyg0pd) {
  fill: currentColor;
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w9g5wtasy) {
  d: path("M14 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.z640i9ymj) {
  fill: currentColor;
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
