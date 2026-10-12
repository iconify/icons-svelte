<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="linzx2b0n"/><path class="vwwywcbip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:guitar-pick" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.linzx2b0n) {
  d: path("M12 21.25c-1.25 0-7.1-8.15-7.95-11.9c-.9-4.1 2.95-6.6 7.95-6.6s8.85 2.5 7.95 6.6c-.85 3.75-6.7 11.9-7.95 11.9");
}

:global(.vwwywcbip) {
  d: path("M9 8.5q3 1.5 6 0");
}

</style>
