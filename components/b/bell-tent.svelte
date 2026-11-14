<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pb_9jfgem"/><path class="opi6knb3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bell-tent" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.opi6knb3w) {
  d: path("m8.5 20.5l3.5-7l3.5 7");
}

:global(.pb_9jfgem) {
  d: path("M3 20.5V16q1.5-5 9-12q7.5 7 9 12v4.5Zm9-18v11");
}

</style>
