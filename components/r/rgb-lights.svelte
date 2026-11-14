<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a94kzbb-h"/><path class="xv2md9bcf"/><path class="e4waztb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rgb-lights" {...props}></Icon>
<style>
:global(.a94kzbb-h) {
  d: path("M6.5 8.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.e4waztb-a) {
  d: path("M10.25 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xv2md9bcf) {
  d: path("M2.75 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
