<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4z3yfbwn"/><path class="kpspt_bpo"/><path class="sd8rzobni"/><path class="bcvts4b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:load-shed-outline-thin" {...props}></Icon>
<style>
:global(.bcvts4b4i) {
  d: path("M13 18.5V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kpspt_bpo) {
  d: path("M7 8h10");
}

:global(.sd8rzobni) {
  d: path("M17 17v2.5");
}

:global(.u4z3yfbwn) {
  d: path("M4 5v9h16V5");
}

</style>
