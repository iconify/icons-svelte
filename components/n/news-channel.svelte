<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-lg1i2qf"/><path class="htgufsa3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:news-channel" {...props}></Icon>
<style>
:global(.htgufsa3d) {
  d: path("m10.25 10.75l5 3.5l-5 3.5Z");
}

:global(.p-lg1i2qf) {
  d: path("M2.5 7.5h19V21h-19Zm6-4.5L12 7.5L15.5 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
