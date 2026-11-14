<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ke58ybbzd"/><path class="h76wi9bcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-home" {...props}></Icon>
<style>
:global(.h76wi9bcp) {
  d: path("M6 12h10v5.5H6Zm10 1.5h1.5V16H16");
}

:global(.ke58ybbzd) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
