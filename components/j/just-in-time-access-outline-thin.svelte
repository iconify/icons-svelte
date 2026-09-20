<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqawgnb7o"/><path class="yq7pxxbcq"/><path class="rlxl2sbpp"/><path class="huj3g_bus"/><path class="xtyo_2ujy"/><path class="r_b-c709a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:just-in-time-access-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.huj3g_bus) {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kqawgnb7o) {
  d: path("M4 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.r_b-c709a) {
  d: path("M20 17v2.5");
}

:global(.rlxl2sbpp) {
  d: path("M8 8h2.5");
}

:global(.xtyo_2ujy) {
  d: path("M17 17h4.5");
}

:global(.yq7pxxbcq) {
  d: path("M8 5.5V8");
}

</style>
