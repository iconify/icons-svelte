<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qoibgxtiv"/><path class="vw7h_8lgs"/><path class="p949upesk"/><path class="e-o23pb7t"/><path class="dpo98j1ht"/><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jet-bridge-duotone-bold" {...props}></Icon>
<style>
:global(.ah-zd_bma) {
  d: path("M13 9v7");
}

:global(.czysiurpc) {
  d: path("M3 9h15v7H3");
}

:global(.dpo98j1ht) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e-o23pb7t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i699y-pkg) {
  d: path("M21 6v13");
}

:global(.p949upesk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qoibgxtiv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

:global(.vw7h_8lgs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h15v7H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yg08zkbcc) {
  d: path("M8 9v7");
}

</style>
