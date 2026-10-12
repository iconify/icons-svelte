<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i84_-sbbe"/><path class="inichvbyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-turn-down" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i84_-sbbe) {
  d: path("M6.25 4.25a8 8 0 0 1 8 8v7");
}

:global(.inichvbyb) {
  d: path("m10.5 15.5l3.75 3.75L18 15.5");
}

</style>
