<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z6zf6db1g"/><path class="d7z7pnqyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:home-alt" {...props}></Icon>
<style>
:global(.d7z7pnqyw) {
  d: path("M5 9.5V19a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9.5M12 15v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z6zf6db1g) {
  d: path("m2.5 11.5l9.5-8l9.5 8");
}

</style>
