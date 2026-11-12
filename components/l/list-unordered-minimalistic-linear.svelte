<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qps5lmbju"/><path class="zhrd6xn3e"/><path class="p-202iw1z"/><path class="akly-1bxp"/><path class="tlafrnbwh"/><path class="ags-59u9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-unordered-minimalistic-linear" {...props}></Icon>
<style>
:global(.ags-59u9n) {
  d: path("M5 16H5.0001");
}

:global(.akly-1bxp) {
  d: path("M5 6H5.0001");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-202iw1z) {
  d: path("M10 16H20");
}

:global(.qps5lmbju) {
  d: path("M10 6H20");
}

:global(.tlafrnbwh) {
  d: path("M5 11H5.0001");
}

:global(.zhrd6xn3e) {
  d: path("M10 11H20");
}

</style>
