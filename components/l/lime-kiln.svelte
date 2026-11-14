<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d_s7yktpk"/><path class="xwml3ikuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lime-kiln" {...props}></Icon>
<style>
:global(.d_s7yktpk) {
  d: path("M6.5 21.5L8.5 9h7l2 12.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xwml3ikuu) {
  d: path("M10 21.5V18a2 2 0 0 1 4 0v3.5M11 6.25c0-2.25 4-1.5 4-3.75");
}

</style>
