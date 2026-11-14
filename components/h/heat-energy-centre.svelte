<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rec4hebat"/><path class="ovvicntxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heat-energy-centre" {...props}></Icon>
<style>
:global(.ovvicntxu) {
  d: path("M6 21.5V17h3.5v4.5");
}

:global(.rec4hebat) {
  d: path("M2.5 21.5V12l5-3.5V12l5-3.5V12h1V3.5H16V12h2.75V6h2.75v15.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
