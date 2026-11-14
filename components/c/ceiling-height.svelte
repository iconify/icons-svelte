<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l7f4kbbfh"/><path class="ug169qsnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ceiling-height" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7f4kbbfh) {
  d: path("M4.75 2.5h14.5A1.75 1.75 0 0 1 21 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75V4.25A1.75 1.75 0 0 1 4.75 2.5m7.25 3v13");
}

:global(.ug169qsnj) {
  d: path("M9.5 8L12 5.5L14.5 8m-5 8l2.5 2.5l2.5-2.5");
}

</style>
