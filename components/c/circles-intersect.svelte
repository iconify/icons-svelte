<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="an1njnd3j"/><path class="fzrpjd9it"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:circles-intersect" {...props}></Icon>
<style>
:global(.an1njnd3j) {
  d: path("M2.5 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.fzrpjd9it) {
  d: path("M9.5 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
