<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8dn9jbyp"/><path class="sg1q03b0n"/><path class="zgowxqjxj"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:in-flight-meal-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.sg1q03b0n) {
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
}

:global(.zgowxqjxj) {
  d: path("M15.5 15V8H21v7");
}

</style>
