<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mcucslbbh"/><path class="ntethobrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:component-variant-add" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mcucslbbh) {
  d: path("m11.311 3.561l5.628 5.628a1.5 1.5 0 0 1 0 2.122l-5.628 5.628a1.5 1.5 0 0 1-2.122 0l-5.628-5.628a1.5 1.5 0 0 1 0-2.122l5.628-5.628a1.5 1.5 0 0 1 2.122 0");
}

:global(.ntethobrf) {
  d: path("m11.311 8.811l.378.378a1.5 1.5 0 0 1 0 2.122l-.378.378a1.5 1.5 0 0 1-2.122 0l-.378-.378a1.5 1.5 0 0 1 0-2.122l.378-.378a1.5 1.5 0 0 1 2.122 0M18 15v6m-3-3h6");
}

</style>
