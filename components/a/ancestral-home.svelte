<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hee4h9bjd"/><path class="vhnf_mbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ancestral-home" {...props}></Icon>
<style>
:global(.hee4h9bjd) {
  d: path("M10.444 20.5H3.5v-10L12 3.25l8.5 7.25v2.456");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vhnf_mbwi) {
  d: path("m18 14.25l3.5 5.25h-7Zm0 5.25v2.25");
}

</style>
