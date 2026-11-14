<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rea3x2bzc"/><path class="hp_udv2wl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-inline" {...props}></Icon>
<style>
:global(.hp_udv2wl) {
  d: path("M8.25 9.25L5.5 12l2.75 2.75m7.5-5.5L18.5 12l-2.75 2.75M13 9.25l-2 5.5");
}

:global(.rea3x2bzc) {
  d: path("M2.5 6.5h19v11h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
