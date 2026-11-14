<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b50y6u5ra"/><path class="gn_79dbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cocoon" {...props}></Icon>
<style>
:global(.b50y6u5ra) {
  d: path("M7 13.5a5 7.5 0 1 0 10 0a5 7.5 0 1 0-10 0m5-11V6");
}

:global(.gn_79dbkv) {
  d: path("M7.25 11q4.75 2.5 9.5 0m-9.5 5q4.75 2.5 9.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
