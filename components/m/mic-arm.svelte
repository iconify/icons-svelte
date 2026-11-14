<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tb1mfpluh"/><path class="gizcrpbsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mic-arm" {...props}></Icon>
<style>
:global(.gizcrpbsx) {
  d: path("M16.5 11v2.5L5.5 10l3 11.5m-5 0h10M14 6.75h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tb1mfpluh) {
  d: path("M16.5 2.5zA2.5 2.5 0 0 1 19 5v3.5a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 14 8.5V5a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
