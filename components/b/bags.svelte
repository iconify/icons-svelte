<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9k8jk4mn"/><path class="dqv2xfb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bags" {...props}></Icon>
<style>
:global(.dqv2xfb4u) {
  d: path("M8.75 9.75V6.5a3.25 3.25 0 0 1 6.5 0v3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o9k8jk4mn) {
  d: path("M5.1 8.4a1.75 1.75 0 0 1 1.74-1.65h10.32A1.75 1.75 0 0 1 18.9 8.4l.7 10.3a2.5 2.5 0 0 1-2.5 2.55H6.9a2.5 2.5 0 0 1-2.5-2.55Z");
}

</style>
