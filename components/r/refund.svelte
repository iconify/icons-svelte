<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kog5qfbcn"/><path class="m2wgly_mi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:refund" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kog5qfbcn) {
  d: path("M6.75 2.75h10.5a2 2 0 0 1 2 2v16.5l-2.4-1.5l-2.45 1.5l-2.4-1.5l-2.4 1.5l-2.45-1.5l-2.4 1.5V4.75a2 2 0 0 1 2-2");
}

:global(.m2wgly_mi) {
  d: path("m10.75 7.25l-2 2l2 2m-2-2h4.5a2.25 2.25 0 0 1 0 4.5h-1.5");
}

</style>
