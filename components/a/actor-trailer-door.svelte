<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pe3706brl"/><path class="qhkowbbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:actor-trailer-door" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pe3706brl) {
  d: path("M6.875 4h7.25A4.375 4.375 0 0 1 18.5 8.375v3.25A4.375 4.375 0 0 1 14.125 16h-7.25A4.375 4.375 0 0 1 2.5 11.625v-3.25A4.375 4.375 0 0 1 6.875 4M18.5 13.5h3");
}

:global(.qhkowbbic) {
  d: path("M13 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5.5-2V7.5H11V16M7.5 7.5L5 9v8.5L7.5 16");
}

</style>
