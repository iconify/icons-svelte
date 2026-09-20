<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xyeuuzvcq"/><path class="gsa3wh0sx"/><path class="quu8uycwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-pool-outline-thin" {...props}></Icon>
<style>
:global(.gsa3wh0sx) {
  d: path("M17.77 4.78a3 3 0 1 1 -2.54 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.quu8uycwi) {
  d: path("M3 14v5h18v-5");
}

:global(.xyeuuzvcq) {
  d: path("M8.77 4.78a3 3 0 1 1 -2.54 0");
}

</style>
