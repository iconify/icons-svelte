<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtieafbyl"/><path class="rqmk01nxq"/><path class="ixsd9xbfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cell-select" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixsd9xbfj) {
  fill: currentColor;
  d: path("M19.5 15h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-.5A1.5 1.5 0 0 1 18 17v-.5a1.5 1.5 0 0 1 1.5-1.5");
}

:global(.rqmk01nxq) {
  d: path("M5.5 8.5h12A1.5 1.5 0 0 1 19 10v4a1.5 1.5 0 0 1-1.5 1.5h-12A1.5 1.5 0 0 1 4 14v-4a1.5 1.5 0 0 1 1.5-1.5");
}

:global(.vtieafbyl) {
  d: path("M5.125 7h12.75A2.625 2.625 0 0 1 20.5 9.625v4.75A2.625 2.625 0 0 1 17.875 17H5.125A2.625 2.625 0 0 1 2.5 14.375v-4.75A2.625 2.625 0 0 1 5.125 7");
}

</style>
