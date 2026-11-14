<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uaf9exbnn"/><path class="imp77ccbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bush-baby" {...props}></Icon>
<style>
:global(.imp77ccbv) {
  d: path("M6 9.5c-2.5-2.5-2.5-7 .25-7C8.75 2.5 9 5.5 7.5 8M18 9.5c2.5-2.5 2.5-7-.25-7c-2.5 0-2.75 3-1.25 5.5M7 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.uaf9exbnn) {
  d: path("M4.5 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
