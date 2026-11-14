<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pjjbkvb_k"/><path class="z3cyklbip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marketing-mix" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pjjbkvb_k) {
  d: path("M10.25 5.5v7.75H18a7.75 7.75 0 1 1-7.75-7.75");
}

:global(.z3cyklbip) {
  d: path("M13 10.5V2.75a7.75 7.75 0 0 1 7.75 7.75ZM2.5 13.25h7.75m0 0V21");
}

</style>
