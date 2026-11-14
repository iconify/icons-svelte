<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wc23aqbga"/><path class="gv6ht1_st"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cost-anomaly" {...props}></Icon>
<style>
:global(.gv6ht1_st) {
  d: path("m7 16l3-2.5L12.5 5l2.5 7.5l3.5-3m-.5 5.25v3.5M18 21h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wc23aqbga) {
  d: path("M3.5 3v17.5H13");
}

</style>
