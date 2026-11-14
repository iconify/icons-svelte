<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9tr9tbtn"/><path class="j17mt-bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ball-trajectory" {...props}></Icon>
<style>
:global(.c9tr9tbtn) {
  d: path("M11 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j17mt-bad) {
  d: path("M13 4q2 4 0 8m6-8q-2 4 0 8M2.5 21q1.5-8 6-9.5");
}

</style>
