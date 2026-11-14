<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elhi6-c-i"/><path class="a2z5s4bbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:golf-slice" {...props}></Icon>
<style>
:global(.a2z5s4bbj) {
  d: path("m14 3l2.5 2L14 7");
}

:global(.elhi6-c-i) {
  d: path("M9 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m2.5-5.75C9.5 9.5 8 5.5 16 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
