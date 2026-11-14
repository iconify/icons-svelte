<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ubazlinms"/><path class="djkoa1b_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:card-cvv" {...props}></Icon>
<style>
:global(.djkoa1b_x) {
  d: path("M13 12.5h5.5V16H13Z");
}

:global(.ubazlinms) {
  d: path("M2.5 5h19v14h-19Zm0 4.5h19M6 15h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
