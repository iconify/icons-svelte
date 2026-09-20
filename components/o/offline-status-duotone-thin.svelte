<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tdmbo5b2c"/><path class="no0si0x2b"/><path class="qpemshbvq"/><path class="gcy62xbec"/><path class="qqsn8sb7q"/><path class="n9-aiskbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:offline-status-duotone-thin" {...props}></Icon>
<style>
:global(.gcy62xbec) {
  d: path("M6.5 16a4.5 4.5 0 0 1 9 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n9-aiskbi) {
  d: path("m17 20 4 -4");
}

:global(.no0si0x2b) {
  fill: currentColor;
  d: path("M17 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qpemshbvq) {
  d: path("M8 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.qqsn8sb7q) {
  d: path("M17 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.tdmbo5b2c) {
  fill: currentColor;
  d: path("M8 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
