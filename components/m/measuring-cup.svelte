<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j1g24abzp"/><path class="muu77ci-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:measuring-cup" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1g24abzp) {
  d: path("M5 4.75h10q1.25 0 1.17 1.25l-.84 13.75Q15.25 21 14 21H7.25Q6 21 5.83 19.76L3.92 5.99Q3.75 4.75 5 4.75");
}

:global(.muu77ci-v) {
  d: path("M15.95 8.5h2.55a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-2.95m-5.3-6.25h3.25m-2 3.25h2m-3.25 3.25h3.25");
}

</style>
