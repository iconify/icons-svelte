<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czo2s0b0e"/><path class="i7n1d_bbc"/><path class="ucgcbdi9f"/><path class="wt76_hbmn"/><path class="g9c4ykb9u"/><path class="m27ljac1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logout-duotone-thin" {...props}></Icon>
<style>
:global(.czo2s0b0e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g9c4ykb9u) {
  d: path("M11 12h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7n1d_bbc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m27ljac1c) {
  d: path("m18 9 3 3 -3 3");
}

:global(.ucgcbdi9f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wt76_hbmn) {
  d: path("M9 3H3v18h6");
}

</style>
