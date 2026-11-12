<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k32cqsb-b"/><path class="msvkvmbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-up-broken" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k32cqsb-b) {
  d: path("M19 13L12 7L10.25 8.5M5 13L7.33333 11");
}

:global(.msvkvmbbw) {
  d: path("M5 17L12 11L13.75 12.5M19 17L16.6667 15");
}

</style>
