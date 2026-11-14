<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8fz1ytrq"/><path class="r6t8z9bxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-brake" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8fz1ytrq) {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m4.75 3.5v-7");
}

:global(.r6t8z9bxl) {
  d: path("M10.25 8.5h2.5a2 2 0 0 1 0 4h-2.5m-3.699 7.282a9.5 9.5 0 0 1 0-15.564m10.898 0a9.5 9.5 0 0 1 0 15.564");
}

</style>
