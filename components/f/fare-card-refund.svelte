<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ahuvu_bjv"/><path class="nwjh2jbvu"/><path class="hn8y3497e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fare-card-refund" {...props}></Icon>
<style>
:global(.ahuvu_bjv) {
  d: path("M9.125 8.5h5.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 12.875v-1.75A2.625 2.625 0 0 1 9.125 8.5M6.5 11h11");
}

:global(.hn8y3497e) {
  d: path("m3.5 3.75l.25 3.5L7 5.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwjh2jbvu) {
  d: path("M7.25 20.25a9.5 9.5 0 1 0-3.5-13");
}

</style>
