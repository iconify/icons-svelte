<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xeb-fib6w"/><path class="mk7_ts7zy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podium-1-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.mk7_ts7zy) {
  d: path("M15.7805 3.5968L17.5 2L17.5 8");
}

:global(.xeb-fib6w) {
  stroke-linejoin: miter;
  d: path("M1 22L23 22M4 22L4 18.5L9 18.5L9 15L14 15L14 11.5L20 11.5L20 22L4 22Z");
}

</style>
