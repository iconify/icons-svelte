<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kue8osbsw"/><path class="rj4amsbyj"/><path class="hfl9jy13x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coin-hoard" {...props}></Icon>
<style>
:global(.hfl9jy13x) {
  d: path("M3.5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.kue8osbsw) {
  d: path("M5 11c-2.5 3-2 9.5 3.5 9.5h7c5.5 0 6-6.5 3.5-9.5M3.5 11h17");
}

:global(.rj4amsbyj) {
  d: path("M8.25 7.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
