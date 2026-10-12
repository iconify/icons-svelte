<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8cpct04c"/><path class="jqtnobcpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:juice" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8cpct04c) {
  d: path("M5.75 7.75h12.5l-1.4 12.1a1.5 1.5 0 0 1-1.5 1.4h-6.7a1.5 1.5 0 0 1-1.5-1.4Z");
}

:global(.jqtnobcpa) {
  d: path("m12.75 12.25l2-9.5h3M6.4 12.25h11.2");
}

</style>
