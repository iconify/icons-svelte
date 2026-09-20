<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="mffjjib6p"/><circle class="dz8jdlt8x"/><circle class="kgq84h0tf"/><path class="fl4-c_bup"/><circle class="mvsxxhbka"/><circle class="cd8gucj9t"/><path class="v9oloac-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:dim-button" {...props}></Icon>
<style>
:global(.cd8gucj9t) {
  cx: 31px;
  cy: 18px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

:global(.dz8jdlt8x) {
  cx: 18px;
  cy: 5px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

:global(.fl4-c_bup) {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M10.222 7.394a2 2 0 1 0-2.828 2.828a2 2 0 0 0 2.828-2.828m18.384 18.384a2 2 0 1 1-2.828 2.828a2 2 0 0 1 2.828-2.828");
}

:global(.kgq84h0tf) {
  cx: 18px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

:global(.mffjjib6p) {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M18 8C12.477 8 8 12.477 8 18s4.477 10 10 10s10-4.477 10-10S23.523 8 18 8m0 16a6 6 0 1 1 0-12a6 6 0 0 1 0 12");
}

:global(.mvsxxhbka) {
  cx: 5px;
  cy: 18px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

:global(.v9oloac-m) {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M28.605 10.222a2 2 0 1 0-2.83-2.829a2 2 0 0 0 2.83 2.829M10.222 28.606a2 2 0 1 1-2.828-2.828a2 2 0 0 1 2.828 2.828");
}

</style>
