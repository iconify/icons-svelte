<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6fsx0sfb"/><path class="gb5ngdcjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corner-up-left" {...props}></Icon>
<style>
:global(.gb5ngdcjv) {
  d: path("M8.5 13L4.75 9.25L8.5 5.5");
}

:global(.h6fsx0sfb) {
  d: path("M19.75 19.75v-8a2.5 2.5 0 0 0-2.5-2.5H4.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
