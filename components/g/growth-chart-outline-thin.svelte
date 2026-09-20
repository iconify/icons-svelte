<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qe97cg-lx"/><path class="dqeovmbtl"/><path class="fua3x2iyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:growth-chart-outline-thin" {...props}></Icon>
<style>
:global(.dqeovmbtl) {
  d: path("m5 18 4 -4 3 3 7 -7");
}

:global(.fua3x2iyd) {
  d: path("M17 6h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

</style>
