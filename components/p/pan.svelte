<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="nj5ucobzf"/><path class="q4kz8wxxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pan" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nj5ucobzf) {
  cx: 9.75px;
  cy: 14.25px;
  r: 7px;
}

:global(.q4kz8wxxu) {
  d: path("M9.75 10a4.25 4.25 0 1 1 0 8.5a4.25 4.25 0 1 1 0-8.5m5-.75L16.5 7.5m1.13.63l3-3a1.25 1.25 0 0 0-1.76-1.76l-3 3a1.25 1.25 0 0 0 1.76 1.76");
}

</style>
