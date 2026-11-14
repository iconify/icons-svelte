<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qaq28qbfw"/><path class="clm01dmtd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cake-box-window" {...props}></Icon>
<style>
:global(.clm01dmtd) {
  d: path("M3 12q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0M3 16.25h18");
}

:global(.qaq28qbfw) {
  d: path("m3 9l16.5-5L21 9v10.5H3Zm0 0h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
