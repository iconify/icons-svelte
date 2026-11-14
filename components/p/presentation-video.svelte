<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lhicevmib"/><path class="y0b590hnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:presentation-video" {...props}></Icon>
<style>
:global(.lhicevmib) {
  d: path("M2.5 2.5h19V16h-19Zm4.5 19L9 16m8 5.5L15 16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0b590hnl) {
  d: path("M9.5 5.5L16 9.25L9.5 13Z");
}

</style>
