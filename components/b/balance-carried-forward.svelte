<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdkku5bwh"/><path class="bmgspob9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:balance-carried-forward" {...props}></Icon>
<style>
:global(.bmgspob9t) {
  d: path("m15.25 6.5l2.5 2.5l2.5-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sdkku5bwh) {
  d: path("M2.5 11.75h5l2.5 2.5v7H2.5Zm11.5 0h5l2.5 2.5v7H14ZM6.25 8.5a5.75 5.75 0 0 1 11.5 0");
}

</style>
