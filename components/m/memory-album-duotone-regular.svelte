<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x5ujzyh2u"/><path class="yajmtkb-r"/><path class="uk66x15py"/><path class="wuvisubmw"/><path class="jxgkv6s4q"/><path class="sxbibil-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-album-duotone-regular" {...props}></Icon>
<style>
:global(.jxgkv6s4q) {
  d: path("M11 8v8h6V8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sxbibil-o) {
  d: path("m11 14 2 -2 3 3");
}

:global(.uk66x15py) {
  d: path("M4 3v18h16V3Z");
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.x5ujzyh2u) {
  fill: currentColor;
  d: path("M4 3v18h16V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yajmtkb-r) {
  fill: currentColor;
  d: path("M11 8v8h6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
