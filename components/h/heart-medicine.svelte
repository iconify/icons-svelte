<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8sl23ngq"/><path class="g0hkn32hq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heart-medicine" {...props}></Icon>
<style>
:global(.e8sl23ngq) {
  d: path("M12 20c-6-4.5-9.5-7.5-9.5-11.5a5 5 0 0 1 9.5-2a5 5 0 0 1 9.5 2c0 4-3.5 7-9.5 11.5");
}

:global(.g0hkn32hq) {
  d: path("M9.172 12.5L12 9.672a2 2 0 0 1 2.828 0a2 2 0 0 1 0 2.828L12 15.328a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828m1.414-1.414l2.828 2.828");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
