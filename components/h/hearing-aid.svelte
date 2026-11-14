<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ukpbnby2x"/><path class="qa8oxdldr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hearing-aid" {...props}></Icon>
<style>
:global(.qa8oxdldr) {
  d: path("M7 19a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 7 19Z");
}

:global(.ukpbnby2x) {
  d: path("M14 3c4 0 6.5 3 6 7c-.5 3.5-2.5 6.25-4.75 7.75l-1.5-1.5C15.5 14.5 17 12 17 9.5c0-2.75-1.25-4.25-3.25-4.25Zm-.25 1c-4.75-.5-7.5 2.5-7 7c.25 3 1 4.5 1.75 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
