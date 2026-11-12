<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1tvwhbhe"/><path class="qru4p6brf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-down-broken" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qru4p6brf) {
  d: path("M5 7L12 13L13.75 11.5M19 7L16.6667 9");
}

:global(.t1tvwhbhe) {
  d: path("M19 11L12 17L10.25 15.5M5 11L7.33333 13");
}

</style>
