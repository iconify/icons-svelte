<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="sx-y9j8pk"/><circle class="himk38dep"/><circle class="f92abbvtk"/><path class="grzk6pbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ddf-guide" {...props}></Icon>
<style>
:global(.f92abbvtk) {
  cx: 38.462px;
  cy: 32.9px;
  r: 0.75px;
  fill: currentColor;
}

:global(.grzk6pbta) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 19.388c0-1.374.458-2.748 1.374-3.664S7.935 14.35 9.54 14.35c2.748 0 5.038 2.29 5.038 5.038c0 1.374-.458 2.748-1.374 3.665c-1.145.916-3.664 2.29-3.664 4.35m9.422-8.015c0-1.374.458-2.748 1.374-3.664S22.396 14.35 24 14.35c2.748 0 5.039 2.29 5.039 5.038c0 1.374-.459 2.748-1.375 3.665c-1.145.916-3.664 2.29-3.664 4.35m9.423-8.015c0-1.374.458-2.748 1.374-3.664s2.061-1.374 3.665-1.374c2.748 0 5.038 2.29 5.038 5.038c0 1.374-.458 2.748-1.374 3.665c-1.145.916-3.664 2.29-3.664 4.35");
}

:global(.himk38dep) {
  cx: 24px;
  cy: 32.9px;
  r: 0.75px;
  fill: currentColor;
}

:global(.sx-y9j8pk) {
  cx: 9.539px;
  cy: 32.9px;
  r: 0.75px;
  fill: currentColor;
}

</style>
