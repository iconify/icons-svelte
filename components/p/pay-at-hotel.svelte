<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-z2e4njp"/><path class="x_c2yubrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pay-at-hotel" {...props}></Icon>
<style>
:global(.e-z2e4njp) {
  d: path("M11.4 17.5H2.5v-14h19V14m-19-6h19M6 13h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_c2yubrz) {
  d: path("M14.25 18L18 14.5l3.75 3.5v3.75h-7.5Z");
}

</style>
