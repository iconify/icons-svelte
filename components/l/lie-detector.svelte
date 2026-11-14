<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cdq3bvbvm"/><path class="v-wr5abnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lie-detector" {...props}></Icon>
<style>
:global(.cdq3bvbvm) {
  d: path("M5.625 14h12.75A2.625 2.625 0 0 1 21 16.625v.75A2.625 2.625 0 0 1 18.375 20H5.625A2.625 2.625 0 0 1 3 17.375v-.75A2.625 2.625 0 0 1 5.625 14M6 14V4h12v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-wr5abnc) {
  d: path("M6 9.5h2.5l1.5-2l2 3.5l1.5-3.5l1.5 2h3");
}

</style>
