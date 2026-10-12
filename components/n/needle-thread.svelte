<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nbudbrb7k"/><path class="xbfew8b1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:needle-thread" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nbudbrb7k) {
  d: path("M3.25 20.75L16.66 7.34a2.25 1.25-45 1 1 3.18-3.18a2.25 1.25-45 1 1-3.18 3.18");
}

:global(.xbfew8b1e) {
  d: path("M18.25 5.75C14 2 7 3.5 7.75 8.25S5.5 15 3 13.75");
}

</style>
