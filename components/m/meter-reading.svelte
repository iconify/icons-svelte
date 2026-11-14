<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kodrrsbvl"/><path class="pxl_z7oip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:meter-reading" {...props}></Icon>
<style>
:global(.kodrrsbvl) {
  d: path("M11.7 21H3V3h18v9.6");
}

:global(.pxl_z7oip) {
  d: path("M6 6.5h12V12H6Zm4 0V12m4-5.5V12m.5 9.5v-2l4.75-4.75l2 2l-4.75 4.75Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
