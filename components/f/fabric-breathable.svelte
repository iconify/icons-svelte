<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yd-ecgb4e"/><path class="iphoevbuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fabric-breathable" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iphoevbuu) {
  d: path("M6.5 7.75c3-1.5 8 1.5 11 0M6.5 12c3-1.5 8 1.5 11 0m-11 4.25c3-1.5 8 1.5 11 0");
}

:global(.yd-ecgb4e) {
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17V7a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
