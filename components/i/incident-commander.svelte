<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lut9_1cos"/><path class="jxg_80b3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:incident-commander" {...props}></Icon>
<style>
:global(.jxg_80b3m) {
  d: path("m6 15.25l6 3.25l6-3.25");
}

:global(.lut9_1cos) {
  d: path("M8.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM3.5 21c0-4.75 3.75-8 8.5-8s8.5 3.25 8.5 8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
