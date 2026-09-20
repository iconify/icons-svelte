<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cxlo_jble"/><path class="k1wxq1ben"/><path class="ru_nxnbim"/><path class="ex75cacie"/><path class="ohbum8bmx"/><path class="b2pxrbbhs"/><path class="nu6kj0bjf"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logits-duotone-regular" {...props}></Icon>
<style>
:global(.b2pxrbbhs) {
  d: path("M11 5v13");
}

:global(.cxlo_jble) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ex75cacie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k1wxq1ben) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 5v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nu6kj0bjf) {
  d: path("M16 11v7");
}

:global(.ohbum8bmx) {
  d: path("M6 8v10");
}

:global(.ru_nxnbim) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
