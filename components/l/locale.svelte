<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cq9hjhbha"/><path class="tkaafvn8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:locale" {...props}></Icon>
<style>
:global(.cq9hjhbha) {
  d: path("M2.5 9.25a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tkaafvn8g) {
  d: path("M6.5 9.25a2.75 6.75 0 1 0 5.5 0a2.75 6.75 0 1 0-5.5 0m-4 0H16m2.5 12.5s-2.5-2-2.5-4a2.5 2.5 0 0 1 5 0c0 2-2.5 4-2.5 4");
}

</style>
