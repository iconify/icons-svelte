<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mls8q-b8u"/><path class="inhyoqqqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.inhyoqqqm) {
  d: path("M8.5 10.5L12 14v5.5m0-5.5l7.5-5.5");
}

:global(.mls8q-b8u) {
  d: path("M2.5 19.5L4 13l4.5-2.5L11 6l5-1.5l3.5 4l2 5.5l-1.5 5.5Z");
}

</style>
