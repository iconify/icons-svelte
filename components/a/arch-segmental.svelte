<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j125ac4uy"/><path class="lxxqmab_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arch-segmental" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j125ac4uy) {
  d: path("M5.625 3h12.75A2.625 2.625 0 0 1 21 5.625v12.75A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375V5.625A2.625 2.625 0 0 1 5.625 3");
}

:global(.lxxqmab_s) {
  d: path("M6.5 21v-8a11 11 0 0 1 11 0v8");
}

</style>
