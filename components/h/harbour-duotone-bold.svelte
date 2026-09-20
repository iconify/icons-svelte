<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="slwp6nw7r"/><path class="fkm86-2nl"/><path class="vaqroib7z"/><path class="iyxe9885d"/><path class="i64ili29r"/><path class="ylu4kimdh"/><path class="ig71m4b4e"/><path class="s0tzl36gy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:harbour-duotone-bold" {...props}></Icon>
<style>
:global(.fkm86-2nl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6.5V20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i64ili29r) {
  d: path("M10 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ig71m4b4e) {
  d: path("M7 8.5h10");
}

:global(.iyxe9885d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 13a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s0tzl36gy) {
  d: path("M19 13a7 7 0 0 1 -14 0");
}

:global(.slwp6nw7r) {
  fill: currentColor;
  d: path("M10 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vaqroib7z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ylu4kimdh) {
  d: path("M12 6.5V20");
}

</style>
