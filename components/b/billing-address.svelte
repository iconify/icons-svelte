<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="to0d6488o"/><path class="a31we93em"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:billing-address" {...props}></Icon>
<style>
:global(.a31we93em) {
  d: path("M7.75 10L12 5.75L16.25 10v3.5h-8.5ZM8 17.75h6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.to0d6488o) {
  d: path("M6.75 2.5h10.5A1.75 1.75 0 0 1 19 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 19.75V4.25A1.75 1.75 0 0 1 6.75 2.5");
}

</style>
