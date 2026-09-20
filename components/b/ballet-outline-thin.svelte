<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yya5lpbze"/><path class="i79bw0b_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ballet-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i79bw0b_m) {
  d: path("M10 9C9 6 7 5 5 4");
}

:global(.yya5lpbze) {
  d: path("M3 18c0 -6 3 -9 7 -9 5 0 9 3.5 10 7 0.5 1.5 0 2 -2 2Z");
}

</style>
