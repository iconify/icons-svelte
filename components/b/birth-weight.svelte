<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xqpb3jbxr"/><path class="utrwucb7m"/><path class="wdrefqfmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:birth-weight" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.utrwucb7m) {
  fill: currentColor;
  d: path("M10.25 17.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0");
}

:global(.wdrefqfmw) {
  d: path("M10.25 13.75h.01m1.74-.5h.01m1.74.5h.01");
}

:global(.xqpb3jbxr) {
  d: path("M4 21.5L7 10h10l3 11.5ZM9.5 6.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
