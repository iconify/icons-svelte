<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-ktk_opr"/><path class="im96wybbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:price-tag-string" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.im96wybbr) {
  d: path("M10.5 14.25C9.5 11 7.5 8 5 6.5S3.5 2 6 2.75c2 .5 2 3 .25 4.5m4.25 7h.01M14 12h4.5M14 16.5h3");
}

:global(.x-ktk_opr) {
  d: path("M11.788 7H20a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-8.212a1.5 1.5 0 0 1-1.235-.648l-3.966-5.75a1.5 1.5 0 0 1 0-1.704l3.966-5.75A1.5 1.5 0 0 1 11.788 7");
}

</style>
