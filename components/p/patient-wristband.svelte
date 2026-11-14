<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4ey99b0m"/><path class="mfyq8u55l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:patient-wristband" {...props}></Icon>
<style>
:global(.h4ey99b0m) {
  d: path("M2.5 12c0-3.5 4.25-5.5 9.5-5.5s9.5 2 9.5 5.5");
}

:global(.mfyq8u55l) {
  d: path("M6.5 11.5h11v7h-11Zm-4 .5c0 1.5 1 2.75 3 3.5m16-3.5c0 1.5-1 2.75-3 3.5M8.75 14h6.5m-6.5 2.25h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
