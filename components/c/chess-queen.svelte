<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tz1v7nb_q"/><rect class="e5tfnwbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chess-queen" {...props}></Icon>
<style>
:global(.e5tfnwbmk) {
  width: 14px;
  height: 2.75px;
  x: 5px;
  y: 18.5px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tz1v7nb_q) {
  d: path("m5.52 5.55l3.21 1.9q.52.3.81-.23l2.17-3.94q.29-.53.58 0l2.17 3.94q.29.53.81.23l3.21-1.9q.52-.3.24.23l-2.69 5.19q-.28.53-.28 1.03t.15 1.08l.45 1.84q.15.58-.45.58H8.1q-.6 0-.45-.58l.45-1.84q.15-.58.15-1.08t-.28-1.03L5.28 5.78q-.28-.53.24-.23M8.5 11.5h7");
}

</style>
