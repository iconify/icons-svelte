<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dhalwcbhj"/><path class="sn2fxebfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:podium-sharp" {...props}></Icon>
<style>
:global(.dhalwcbhj) {
  d: path("M2.75 21.25V11.5h6V4.75h6.5v9H21v7.5Z");
}

:global(.sn2fxebfr) {
  d: path("m11 9l1.25-1v5.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
