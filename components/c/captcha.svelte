<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="ecout6oml"/><path class="ytjr9nb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:captcha" {...props}></Icon>
<style>
:global(.ecout6oml) {
  d: path("M5.5 9h6v6h-6Z");
}

:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytjr9nb1j) {
  d: path("M6.75 12L8 13.25l2.25-2.5M14 12h4.5");
}

</style>
