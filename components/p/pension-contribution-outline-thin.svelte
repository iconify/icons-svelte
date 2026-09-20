<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_k4bub3x"/><path class="guw4_4ovg"/><path class="ohhz_s35v"/><path class="mqi2_ac9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pension-contribution-outline-thin" {...props}></Icon>
<style>
:global(.g_k4bub3x) {
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
}

:global(.guw4_4ovg) {
  d: path("M8 9V4h8v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mqi2_ac9e) {
  d: path("M9.5 15.5 12 18l2.5 -2.5");
}

:global(.ohhz_s35v) {
  d: path("M12 12v6");
}

</style>
