<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0mbg97tq"/><path class="o_wdptbqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:farm" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_wdptbqa) {
  d: path("M9.5 8V4.25h2V10m3.25.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M18 13.75v6.75m-12.25 0v-4h3v4");
}

:global(.r0mbg97tq) {
  d: path("m3.013 9.987l3-3a1.75 1.75 0 0 1 2.474 0l3 3A1.75 1.75 0 0 1 12 11.225v7.525a1.75 1.75 0 0 1-1.75 1.75h-6a1.75 1.75 0 0 1-1.75-1.75v-7.525a1.75 1.75 0 0 1 .513-1.238");
}

</style>
