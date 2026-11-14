<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kgfqzybpy"/><path class="guj2_22dh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camera-backpack" {...props}></Icon>
<style>
:global(.guj2_22dh) {
  d: path("M9 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.kgfqzybpy) {
  d: path("M6 5.5h12a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-14a1 1 0 0 1 1-1Zm3.5 0a2.5 2.5 0 0 1 5 0M5 9.5h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
