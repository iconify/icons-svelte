<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pw6b-h5hm"/><path class="j0-uk2hni"/><path class="e9fltbcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mutation-test" {...props}></Icon>
<style>
:global(.e9fltbcec) {
  d: path("m14.75 18l2 2L21 15.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j0-uk2hni) {
  fill: currentColor;
  d: path("M8 8.25h1.75v3.5H8a1.75 1.75 0 0 1 0-3.5");
}

:global(.pw6b-h5hm) {
  d: path("M2.5 2.5h1V15a4.5 4.5 0 0 0 9 0V2.5h1");
}

</style>
