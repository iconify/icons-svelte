<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="orglh600g"/><path class="jl-iu79-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:listing-withdrawn" {...props}></Icon>
<style>
:global(.jl-iu79-w) {
  d: path("m5.5 10.5l4-4l4 4v3.086M11.914 16.5H5.5v-6M16 9h3m-4.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm1.75 0h3.5");
}

:global(.orglh600g) {
  d: path("M11.9 19.5H2.5v-15h19v8.3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
