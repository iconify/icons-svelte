<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-egtfbpv"/><path class="ie87xklmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:colour-wheel-half" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ie87xklmx) {
  d: path("M9 16.75a3 3 0 0 1 6 0m-.75-2.25l4.5-4.5M12 13.75v-6.5M9.75 14.5L5.25 10");
}

:global(.j-egtfbpv) {
  d: path("M2.5 16.75a9.5 9.5 0 0 1 19 0Z");
}

</style>
