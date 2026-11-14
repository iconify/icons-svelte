<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="z-1rhibvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:allergen-shellfish" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.z-1rhibvh) {
  d: path("m12 17.5l-4.75-6C7.25 8.75 9.4 7 12 7s4.75 1.75 4.75 4.5Zm0 0V7m0 10.5L8.75 8.25M12 17.5l3.25-9.25");
}

</style>
