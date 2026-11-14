<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a7br98xvq"/><path class="q4nsz-hoc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:candle-jar" {...props}></Icon>
<style>
:global(.a7br98xvq) {
  d: path("M5 9.75h14V21.5H5Zm7-7.25c1.5 1.5 1.75 2.25 1.75 2.75a1.75 1.75 0 0 1-3.5 0c0-.5.25-1.25 1.75-2.75ZM12 7v2.75");
}

:global(.q4nsz-hoc) {
  d: path("M8 13.5h8v4H8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
