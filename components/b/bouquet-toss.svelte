<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e80lkwbzd"/><path class="usnb69u0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bouquet-toss" {...props}></Icon>
<style>
:global(.e80lkwbzd) {
  d: path("M10.75 5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm5.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.usnb69u0n) {
  d: path("M13.5 9.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm.75 2l-4.5 4.5m0 0l-3-1.5L8 13.25Zm0 0C8 18 6 18.75 3.5 18.5m6.25-2.25c-1 2-1.5 3.5-1.25 5.25m5-1q5-.5 7.5-5m-7 1.25q3-.25 4.5-2.25");
}

</style>
