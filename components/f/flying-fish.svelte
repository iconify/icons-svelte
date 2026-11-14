<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ptf2zyt_e"/><path class="fwiik4b1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flying-fish" {...props}></Icon>
<style>
:global(.fwiik4b1o) {
  d: path("m9 8.25l6.5-4.75L13 9m-6.5 2h.01M3 19q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

:global(.ptf2zyt_e) {
  d: path("M4 11c3-4 8.5-4 11.5 0l5-3.5v7l-5-3.5c-3 4-8.5 4-11.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
