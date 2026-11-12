<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zowiwwbmr"/><path class="zyly0dhik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-down-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zowiwwbmr) {
  d: path("M6 6L18 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.zyly0dhik) {
  d: path("M18 9L18 18L9 18");
}

</style>
