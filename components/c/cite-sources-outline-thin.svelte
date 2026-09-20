<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nyba_zpqc"/><path class="nutam6ble"/><path class="n-7t0yb1r"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cite-sources-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.nutam6ble) {
  d: path("M17 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nyba_zpqc) {
  d: path("M3 8h11");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
