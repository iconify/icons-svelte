<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwyuc_nec"/><path class="wwthhklrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pythagorean-theorem" {...props}></Icon>
<style>
:global(.gwyuc_nec) {
  d: path("M4 18.5V9.306a1.5 1.5 0 0 1 2.488-1.129l10.508 9.194A1.5 1.5 0 0 1 16.008 20H5.5A1.5 1.5 0 0 1 4 18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wwthhklrx) {
  d: path("M5.5 15.5H7A1.5 1.5 0 0 1 8.5 17v1.5A1.5 1.5 0 0 1 7 20H5.5A1.5 1.5 0 0 1 4 18.5V17a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
