<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gxyxyib8k"/><path class="n4-cgibgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:engagement-boost" {...props}></Icon>
<style>
:global(.gxyxyib8k) {
  d: path("M20.5 3.5C16 3.5 12.5 6 10 10l4 4c4-2.5 6.5-6 6.5-10.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n4-cgibgo) {
  d: path("M10.5 9.5H7L4.5 12H8m6.5 1.5V17L12 19.5V16m2.5-8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M5 15h4v4");
}

</style>
