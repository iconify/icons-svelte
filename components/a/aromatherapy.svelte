<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q6evb1tgz"/><path class="e-uvtub8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aromatherapy" {...props}></Icon>
<style>
:global(.e-uvtub8c) {
  d: path("M9.5 18.25c0-3 2-5 5-5c0 3-2 5-5 5Z");
}

:global(.q6evb1tgz) {
  d: path("M6.5 10h11v11.5h-11Zm3-3h5v3h-5Zm.5 0V4.5a2 2 0 0 1 4 0V7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
