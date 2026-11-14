<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="devj7tbyk"/><path class="e9fltbcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:event-booking" {...props}></Icon>
<style>
:global(.devj7tbyk) {
  d: path("M13.8 21H3V4.5h17v8.3m0 7.9v.3h-.3M3 9.5h17m-12.5-7v4m8-4v4");
}

:global(.e9fltbcec) {
  d: path("m14.75 18l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
