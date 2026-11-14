<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6qbr7osf"/><path class="l51r0lxwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:depilatory-cream" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l51r0lxwx) {
  d: path("M10 10c0-1.5 2-1.5 2 0s2 1.5 2 0");
}

:global(.u6qbr7osf) {
  d: path("M8.54 3.5h6.92a1.75 1.75 0 0 1 1.73 2.016l-1.462 9.5a1.75 1.75 0 0 1-1.729 1.484h-3.998a1.75 1.75 0 0 1-1.729-1.484l-1.462-9.5A1.75 1.75 0 0 1 8.54 3.5m2.71 13h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
