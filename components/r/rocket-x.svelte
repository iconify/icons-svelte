<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9m2ndcht"/><path class="j1hnyjv5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rocket-x" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1hnyjv5o) {
  d: path("M6 11.5L3 15v3l3-2m6-4.5l1.6 1.921M9 18.75v2.75m6.5-6l5 5m0-5l-5 5");
}

:global(.z9m2ndcht) {
  d: path("M9 2.5C12.5 5 13 10 12 16H6C5 10 5.5 5 9 2.5");
}

</style>
