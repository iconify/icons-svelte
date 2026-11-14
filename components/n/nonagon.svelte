<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kix0ieubt"/><path class="ey8hbsbby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nonagon" {...props}></Icon>
<style>
:global(.ey8hbsbby) {
  d: path("M8.75 21.5L3.5 17.25l-1-6.75l3.25-5.75L12 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kix0ieubt) {
  d: path("m12 2.5l6.25 2.25l3.25 5.75l-1 6.75l-5.25 4.25h-6.5");
}

</style>
