<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="guqqttbir"/><path class="b6lj25bxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-export" {...props}></Icon>
<style>
:global(.b6lj25bxi) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-1.5 10.25H16a1.5 1.5 0 0 0-1.5 1.5V20a1.5 1.5 0 0 0 1.5 1.5h3.75a1.5 1.5 0 0 0 1.5-1.5v-1.5m-3.5-.25l3.75-3.75m-2.75 0h2.75v2.75");
}

:global(.guqqttbir) {
  d: path("M3.5 3v17.5h8.2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
