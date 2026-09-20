<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fesqdtb9n"/><path class="qy8bklpen"/><path class="et2ai2bem"/><path class="h2sq3fbpa"/><path class="ohbum8bmx"/><path class="b2pxrbbhs"/><path class="nu6kj0bjf"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logits-duotone-bold" {...props}></Icon>
<style>
:global(.b2pxrbbhs) {
  d: path("M11 5v13");
}

:global(.et2ai2bem) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fesqdtb9n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2sq3fbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nu6kj0bjf) {
  d: path("M16 11v7");
}

:global(.ohbum8bmx) {
  d: path("M6 8v10");
}

:global(.qy8bklpen) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 5v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
