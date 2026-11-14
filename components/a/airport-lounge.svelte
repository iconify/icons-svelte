<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ny7dtrxmy"/><path class="khxvphr6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:airport-lounge" {...props}></Icon>
<style>
:global(.khxvphr6i) {
  d: path("M3 13.5h18V18H3ZM6 18v3m12-3v3");
}

:global(.ny7dtrxmy) {
  d: path("M4 16v-6c0-1.5 1-2 2.5-2h11c1.5 0 2.5.5 2.5 2v6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
