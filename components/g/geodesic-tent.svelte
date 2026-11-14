<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rjw-hn10r"/><path class="r4-dgxb6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:geodesic-tent" {...props}></Icon>
<style>
:global(.r4-dgxb6y) {
  d: path("M4.25 12.5L8 8.25l4 4.25l4-4.25l3.75 4.25m-10.25 5l2.5-5l2.5 5");
}

:global(.rjw-hn10r) {
  d: path("M3 17.5a9 10.5 0 0 1 18 0Zm1.25-5h15.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
