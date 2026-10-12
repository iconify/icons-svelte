<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xmm3srbki"/><path class="gcvv_rb-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chevron-down-to-line" {...props}></Icon>
<style>
:global(.gcvv_rb-r) {
  d: path("M5.25 11.75L12 18.5l6.75-6.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xmm3srbki) {
  d: path("M5.25 5.5L12 12.25l6.75-6.75");
}

</style>
