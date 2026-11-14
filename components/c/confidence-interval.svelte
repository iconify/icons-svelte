<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nxaihbbaq"/><path class="a5fsbcbix"/><path class="xsz8hrbvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:confidence-interval" {...props}></Icon>
<style>
:global(.a5fsbcbix) {
  fill: currentColor;
  d: path("M8.5 19.5V9.25C9.5 6 10.5 4 12 4s2.5 2 3.5 5.25V19.5Z");
}

:global(.nxaihbbaq) {
  d: path("M2.5 19.5C7 19.5 8.5 4 12 4s5 15.5 9.5 15.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xsz8hrbvx) {
  d: path("M2.5 19.5h19");
}

</style>
