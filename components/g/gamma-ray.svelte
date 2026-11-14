<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlkep1bth"/><path class="a75jntbgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gamma-ray" {...props}></Icon>
<style>
:global(.a75jntbgd) {
  d: path("m18.5 9l3 3l-3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vlkep1bth) {
  d: path("M2.5 12L5 6.5l3.5 11l3.5-11l3 9l1.75-3.5h4.75");
}

</style>
