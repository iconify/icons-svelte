<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="psq8kqbwm"/><path class="pqzjmfbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:patient-portal" {...props}></Icon>
<style>
:global(.pqzjmfbgh) {
  d: path("M7 12a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 7 12Zm-1 5.5C6 16 7.25 15 8.75 15s2.75 1 2.75 2.5M14 12h4.5M14 15.5h4.5");
}

:global(.psq8kqbwm) {
  d: path("M2.5 3.5h19v17h-19Zm0 4h19M5 5.5h.01m2.49 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
