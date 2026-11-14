<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w5kzggbel"/><path class="brmfyc00r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:padlock-heavy" {...props}></Icon>
<style>
:global(.brmfyc00r) {
  fill: currentColor;
  d: path("M10.25 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w5kzggbel) {
  d: path("M2.5 10h19v11.5h-19ZM6 10V8.5a6 6 0 0 1 12 0V10h-2.75V8.5a3.25 3.25 0 0 0-6.5 0V10Z");
}

</style>
