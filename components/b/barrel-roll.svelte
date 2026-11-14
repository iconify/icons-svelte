<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ah455xb-q"/><path class="ej4wbybdu"/><path class="dm25trbqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:barrel-roll" {...props}></Icon>
<style>
:global(.ah455xb-q) {
  d: path("M2.5 16H8c4 0 7.5-3 7.5-7a3.5 3.5 0 0 0-7 0");
}

:global(.dm25trbqk) {
  d: path("m18 13.5l2.5 2.5l-2.5 2.5");
}

:global(.ej4wbybdu) {
  d: path("M8.5 9c0 4 3.5 7 7.5 7h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
