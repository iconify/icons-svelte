<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nqnw98byf"/><path class="hm2fmmbfq"/><path class="i-2_6c56r"/><path class="pm3a-tbmq"/><path class="j6tvmikgv"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:geothermal-outline-thin" {...props}></Icon>
<style>
:global(.hm2fmmbfq) {
  d: path("M8 12a2.5 2.5 0 0 1 0 -5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-2_6c56r) {
  d: path("M8 2a2.5 2.5 0 0 1 0 5");
}

:global(.j6tvmikgv) {
  d: path("M16 2a2.5 2.5 0 0 1 0 5");
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.pm3a-tbmq) {
  d: path("M16 12a2.5 2.5 0 0 1 0 -5");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

</style>
