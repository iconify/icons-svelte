<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ib2ejzoki"/><path class="tyien_b-s"/><path class="qr6s0i6wc"/><path class="nu0ti3ggl"/><path class="b1af8dhgl"/><path class="vhnbtvbtn"/><path class="teamv5bhf"/><path class="yegul17ht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:litter-tray-duotone-bold" {...props}></Icon>
<style>
:global(.b1af8dhgl) {
  d: path("M5 8v10h14V8");
}

:global(.ib2ejzoki) {
  fill: currentColor;
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nu0ti3ggl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qr6s0i6wc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8v10h14V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.teamv5bhf) {
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.tyien_b-s) {
  fill: currentColor;
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.yegul17ht) {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
