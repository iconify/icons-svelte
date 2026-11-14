<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ykr0mxbbo"/><path class="ihnfzbbqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:laundry-detergent" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ihnfzbbqs) {
  d: path("M10 11s-2.5 3-2.5 4.5a2.5 2.5 0 0 0 5 0C12.5 14 10 11 10 11");
}

:global(.ykr0mxbbo) {
  d: path("M8.75 3h2.5A1.75 1.75 0 0 1 13 4.75v.5A1.75 1.75 0 0 1 11.25 7h-2.5A1.75 1.75 0 0 1 7 5.25v-.5A1.75 1.75 0 0 1 8.75 3M4 21V10a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v11ZM16 9h2a2.5 2.5 0 0 1 2.5 2.5v2A2.5 2.5 0 0 1 18 16h-2");
}

</style>
