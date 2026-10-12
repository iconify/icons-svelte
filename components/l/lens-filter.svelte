<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qqrphjjlv"/><path class="mmu9bo8lf"/><path class="i_86jkpqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lens-filter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_86jkpqu) {
  d: path("M6.5 9.9a5.5 1.75 0 0 1 11 0a5.5 1.75 0 0 1-11 0m2.25 6.35V17m3.25-.5v.75m3.25-1V17m-9.5-1.75v.5m12.5-.5v.5");
}

:global(.mmu9bo8lf) {
  d: path("M2.75 9.9a9.25 4.5 0 0 0 18.5 0");
}

:global(.qqrphjjlv) {
  d: path("M2.75 9.9a9.25 4.5 0 0 1 18.5 0v4.2a9.25 4.5 0 0 1-18.5 0Z");
}

</style>
