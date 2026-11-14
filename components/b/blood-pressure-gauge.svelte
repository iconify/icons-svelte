<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yq25-db3j"/><path class="c14gu6hoo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blood-pressure-gauge" {...props}></Icon>
<style>
:global(.c14gu6hoo) {
  d: path("M7.237 13.75a5.5 5.5 0 1 1 9.526 0M12 11l3-3m-3 3h.01M12 19.5v2.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yq25-db3j) {
  d: path("M3.5 11a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0");
}

</style>
