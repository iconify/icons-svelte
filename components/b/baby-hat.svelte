<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ua_heq3hr"/><path class="kmf8o-20s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-hat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kmf8o-20s) {
  d: path("M10.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.ua_heq3hr) {
  d: path("M5 15v-2.5a7 7 0 0 1 14 0V15M6.5 15h11a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-11a3 3 0 0 1-3-3a3 3 0 0 1 3-3");
}

</style>
