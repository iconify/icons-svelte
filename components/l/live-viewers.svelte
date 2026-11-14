<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw2j_fbcl"/><path class="pjwcy4b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:live-viewers" {...props}></Icon>
<style>
:global(.pjwcy4b8c) {
  d: path("M6.5 12C8 9.5 10 8.25 12 8.25S16 9.5 17.5 12C16 14.5 14 15.75 12 15.75S8 14.5 6.5 12Zm5.5 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uw2j_fbcl) {
  d: path("M3.5 4.5h17a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-13a1 1 0 0 1 1-1Z");
}

</style>
