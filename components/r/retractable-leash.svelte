<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="omj5d9bvx"/><path class="m85e346kk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:retractable-leash" {...props}></Icon>
<style>
:global(.m85e346kk) {
  d: path("M6.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.omj5d9bvx) {
  d: path("M2.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm11 0h3m0-3h5v6h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
