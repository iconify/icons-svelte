<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nv5ey2b_z"/><path class="le4zy58-y"/><path class="r87sa_1ne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:battery-clock" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.le4zy58-y) {
  d: path("M6.75 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.nv5ey2b_z) {
  d: path("M6.875 5h7.75A4.375 4.375 0 0 1 19 9.375v5.25A4.375 4.375 0 0 1 14.625 19h-7.75A4.375 4.375 0 0 1 2.5 14.625v-5.25A4.375 4.375 0 0 1 6.875 5M19 9.5h1.5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H19");
}

:global(.r87sa_1ne) {
  d: path("M10.75 10v2l1.5 1");
}

</style>
