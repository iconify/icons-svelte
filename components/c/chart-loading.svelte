<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o4c588h0r"/><path class="x-xu7rltv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-loading" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o4c588h0r) {
  d: path("M3.5 3v17.5h9");
}

:global(.x-xu7rltv) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m.625 10.685a3.25 3.25 0 1 1-4.44 1.19");
}

</style>
