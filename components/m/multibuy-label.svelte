<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_w9pnbcb"/><path class="gblj43bfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:multibuy-label" {...props}></Icon>
<style>
:global(.gblj43bfj) {
  d: path("M13 9.75c.25-.75 1-1.25 2-1.25c1.25 0 2 .75 2 1.75s-.75 1.5-1.75 1.5c1.25 0 2 .75 2 2c0 1-1 1.75-2.25 1.75c-1 0-1.75-.5-2-1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_w9pnbcb) {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5m-.25 5l4 4m0-4l-4 4");
}

</style>
