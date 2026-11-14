<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fja47rb1a"/><path class="ox61--bau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:neckband-earphones" {...props}></Icon>
<style>
:global(.fja47rb1a) {
  d: path("M5.5 6v6a6.5 6.5 0 0 0 13 0V6");
}

:global(.ox61--bau) {
  d: path("M3.5 2.5h4V7h-4Zm13 0h4V7h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
