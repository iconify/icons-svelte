<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y83ksccnl"/><path class="gblj43bfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:multibuy-label" {...props}></Icon>
<style>
:global(.gblj43bfj) {
  d: path("M13 9.75c.25-.75 1-1.25 2-1.25c1.25 0 2 .75 2 1.75s-.75 1.5-1.75 1.5c1.25 0 2 .75 2 2c0 1-1 1.75-2.25 1.75c-1 0-1.75-.5-2-1.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y83ksccnl) {
  d: path("M2.5 5h19v14h-19Zm3.25 5l4 4m0-4l-4 4");
}

</style>
