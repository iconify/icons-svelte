<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovt_6acny"/><path class="p-570-pmk"/><path class="byh8rvbcw"/><path class="uci4f6n5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:divide-broken" {...props}></Icon>
<style>
:global(.byh8rvbcw) {
  d: path("M12 6H12.0001");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ovt_6acny) {
  d: path("M4 12H12");
}

:global(.p-570-pmk) {
  d: path("M16 12H20");
}

:global(.uci4f6n5q) {
  d: path("M12 18H12.0001");
}

</style>
