<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b1z9phbxy"/><path class="s2g9lw-uk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-glacier" {...props}></Icon>
<style>
:global(.b1z9phbxy) {
  d: path("M2.5 17.5L12 3l9.5 14.5Z");
}

:global(.s2g9lw-uk) {
  d: path("m7.5 10l2 2.5l2.5-2.25l2.5 2.25l2-2.5M4 20.75h7m3 0h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
