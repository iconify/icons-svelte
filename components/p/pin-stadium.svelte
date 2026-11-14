<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u5cqcmbhg"/><path class="w0sxxboip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-stadium" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u5cqcmbhg) {
  d: path("M10 4.5h4a7.5 7.5 0 0 1 7.5 7.5a7.5 7.5 0 0 1-7.5 7.5h-4A7.5 7.5 0 0 1 2.5 12A7.5 7.5 0 0 1 10 4.5");
}

:global(.w0sxxboip) {
  d: path("M10 7.5h4a4.5 4.5 0 0 1 4.5 4.5a4.5 4.5 0 0 1-4.5 4.5h-4A4.5 4.5 0 0 1 5.5 12A4.5 4.5 0 0 1 10 7.5m2 0v9");
}

</style>
