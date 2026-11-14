<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r0rc08b0c"/><path class="ia8hz-bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:designer" {...props}></Icon>
<style>
:global(.ia8hz-bad) {
  d: path("M6 18.5q6-6 12 0m-6-5.75V9m-9.5 7.75H6v3.5H2.5Zm15.5 0h3.5v3.5H18Z");
}

:global(.r0rc08b0c) {
  d: path("m12 12.75l-3.5-5l1.5-4h4l1.5 4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
