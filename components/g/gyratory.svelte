<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vz1dcfb4q"/><path class="gwvx2rbui"/><path class="tfo2qlbsq"/><path class="k1v3zobpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gyratory" {...props}></Icon>
<style>
:global(.gwvx2rbui) {
  d: path("m18 10l2 2l2-2m-3.75 7.25A8 8 0 0 1 8 19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k1v3zobpr) {
  d: path("M5.25 4.25L8 5l-.75 2.75M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.tfo2qlbsq) {
  d: path("M10.75 18.25L8 19l.75 2.75m-4.25-7A8 8 0 0 1 8 5");
}

:global(.vz1dcfb4q) {
  d: path("M13.5 4.25A8 8 0 0 1 20 12");
}

</style>
