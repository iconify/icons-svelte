<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtvuoqbmv"/><path class="qzrr52x1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:laundry-chute" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qzrr52x1z) {
  d: path("M10.75 5.5h2.5A1.75 1.75 0 0 1 15 7.25v1A1.75 1.75 0 0 1 13.25 10h-2.5A1.75 1.75 0 0 1 9 8.25v-1a1.75 1.75 0 0 1 1.75-1.75M12 13v5.75m-2.5-2.5l2.5 2.5l2.5-2.5");
}

:global(.xtvuoqbmv) {
  d: path("M10.75 2.5h2.5a5.25 5.25 0 0 1 5.25 5.25v8.5a5.25 5.25 0 0 1-5.25 5.25h-2.5a5.25 5.25 0 0 1-5.25-5.25v-8.5a5.25 5.25 0 0 1 5.25-5.25");
}

</style>
