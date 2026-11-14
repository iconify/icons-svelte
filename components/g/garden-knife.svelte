<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-vrp6bql"/><path class="jhwnxyams"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garden-knife" {...props}></Icon>
<style>
:global(.f-vrp6bql) {
  d: path("M9 12.5c3.5-3.5 7.5-8 10.5-8C21 4.5 21.5 6 21 8c-1.5-.75-3.5.25-5.5 2.5l-4 4.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jhwnxyams) {
  d: path("m9 12.5l-5.25 5.25a1.75 1.75 0 0 0 2.5 2.5L11.5 15");
}

</style>
