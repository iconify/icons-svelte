<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myezvtihj"/><path class="n2wd1ybou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:award-medal-media" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.myezvtihj) {
  d: path("M5.5 14.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.n2wd1ybou) {
  d: path("M9 8.75L6.5 2.5h3.75L12 6.75l1.75-4.25h3.75L15 8.75m-2.315 4.464l.065.036a1.43 1.43 0 0 1 0 2.5l-.065.036A1.47 1.47 0 0 1 10.5 14.5a1.47 1.47 0 0 1 2.185-1.286");
}

</style>
