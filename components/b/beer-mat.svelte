<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bk9_7iect"/><path class="rznh07bjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beer-mat" {...props}></Icon>
<style>
:global(.bk9_7iect) {
  d: path("M9 14.75a9 3.5 0 1 0 6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rznh07bjb) {
  d: path("M9 18v-8l1.5-2.5v-5h3v5L15 10v8Z");
}

</style>
