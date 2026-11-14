<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n6thrcckn"/><path class="aa8dbmbdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:decline-chart" {...props}></Icon>
<style>
:global(.aa8dbmbdf) {
  d: path("M20 8.5V13h-4.5");
}

:global(.n6thrcckn) {
  d: path("M5.5 20.5V11m5.5 9.5V14m5.5 6.5V17M3.5 4l7 6.5l3.5-3l6 5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
