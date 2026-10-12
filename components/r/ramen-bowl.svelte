<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gc99geuhv"/><path class="cfhrd-b1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ramen-bowl" {...props}></Icon>
<style>
:global(.cfhrd-b1h) {
  d: path("M6.75 15.5q1.5 1.2 3 0c1.5-1.2 2-.8 3 0s2 .8 3 0s2 .8 3 0");
}

:global(.gc99geuhv) {
  d: path("M3.75 12h16.5a.75.75 0 0 1 .75.85a9 7.5 0 0 1-18 0a.75.75 0 0 1 .75-.85m.75-9L8 12m0-9.25L10.25 12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
