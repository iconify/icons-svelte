<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oxjwcvb5u"/><path class="sje5chbik"/><path class="gxgy5_blu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:copper-wire-coil" {...props}></Icon>
<style>
:global(.gxgy5_blu) {
  d: path("M8.5 11a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0Zm10.25 5L21 20");
}

:global(.oxjwcvb5u) {
  d: path("M2.5 11a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0Z");
}

:global(.sje5chbik) {
  d: path("M5.5 11a6.5 4.25 0 1 0 13 0a6.5 4.25 0 1 0-13 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
