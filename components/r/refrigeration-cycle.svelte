<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gofhirb1o"/><path class="knapdbc1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:refrigeration-cycle" {...props}></Icon>
<style>
:global(.gofhirb1o) {
  d: path("M5 4h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm7 4.5v7m-3-5.25l6 3.5m-6 0l6-3.5");
}

:global(.knapdbc1i) {
  d: path("M11 2.25L12.75 4L11 5.75m2 12.5L11.25 20L13 21.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
