<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l28eh75vl"/><path class="k54fio-ph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rookie-of-year" {...props}></Icon>
<style>
:global(.k54fio-ph) {
  d: path("m12 5.75l.75 2h2l-1.5 1.5l.5 2L12 10l-1.75 1.25l.5-2l-1.5-1.5h2ZM6 5H4.5a2 2 0 0 0 0 4H6m12-4h1.5a2 2 0 0 1 0 4H18m-6 6v5m-4 0h8");
}

:global(.l28eh75vl) {
  d: path("M6 3h12v6A6 6 0 0 1 6 9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
