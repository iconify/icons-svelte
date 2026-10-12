<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdrjtvbbc"/><path class="ri_ejgbep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:porridge" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ri_ejgbep) {
  d: path("M8 14.25c1.3.9 2.7.9 4 0s2.7-.9 4 0");
}

:global(.wdrjtvbbc) {
  d: path("M3.75 11.5h16.5a8.25 6.75 0 0 1-16.5 0M9 21.25h6M14 8.5l3.5-5.75");
}

</style>
