<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1f9d0qaa"/><path class="g0f834bgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dependency-scan" {...props}></Icon>
<style>
:global(.g0f834bgv) {
  d: path("M3.5 6L10 9.5L16.5 6M10 9.5v7m5 1.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m4.75 2l1.75 1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n1f9d0qaa) {
  d: path("m10.83 2.947l4.75 2.557a1.75 1.75 0 0 1 .92 1.541v4.91a1.75 1.75 0 0 1-.92 1.541l-4.75 2.557a1.75 1.75 0 0 1-1.66 0l-4.75-2.557a1.75 1.75 0 0 1-.92-1.541v-4.91a1.75 1.75 0 0 1 .92-1.541l4.75-2.557a1.75 1.75 0 0 1 1.66 0");
}

</style>
