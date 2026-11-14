<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jqqdk0m7p"/><path class="ohbwrpjhg"/><path class="i5z768-2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fan-oscillate" {...props}></Icon>
<style>
:global(.i5z768-2u) {
  d: path("m15 18.25l2.5.75l-.75 2.5M9 18.25L6.5 19l.75 2.5");
}

:global(.jqqdk0m7p) {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ohbwrpjhg) {
  d: path("M12 9.5q0-3.5 2.5-3.75M12 9.5q3 1.75 2 4m-2-4q-3 1.75-4.5-.25m10 9.776a11 11 0 0 1-11 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
