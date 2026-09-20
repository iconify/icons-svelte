<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qqjuc6bqq"/><path class="ex75cacie"/><path class="kyboc-b7u"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jitter-duotone-regular" {...props}></Icon>
<style>
:global(.ex75cacie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kyboc-b7u) {
  d: path("m3 15 5 -5 2 2 4 -4 3 3 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qqjuc6bqq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 5 -5 2 2 4 -4 3 3 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
