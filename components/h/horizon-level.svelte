<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uykogrl1p"/><path class="aqpx8mbxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:horizon-level" {...props}></Icon>
<style>
:global(.aqpx8mbxp) {
  d: path("M8 10.25h8v3.5H8ZM12 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uykogrl1p) {
  d: path("M2.5 7.5h19v9h-19Z");
}

</style>
