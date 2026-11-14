<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wxoo7k3or"/><path class="mllqplh8o"/><path class="od4rfdimj"/><path class="grpu8bp7m"/><path class="hs56eykib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:quote-post" {...props}></Icon>
<style>
:global(.grpu8bp7m) {
  fill: currentColor;
  d: path("M13.25 7.5H16v2.75h-2.75Z");
}

:global(.hs56eykib) {
  d: path("M16 10c0 1.75-1 2.75-2.5 3.25");
}

:global(.mllqplh8o) {
  fill: currentColor;
  d: path("M7.5 7.5h2.75v2.75H7.5Z");
}

:global(.od4rfdimj) {
  d: path("M10.25 10c0 1.75-1 2.75-2.5 3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wxoo7k3or) {
  d: path("M4 6a2.5 2.5 0 0 1 2.5-2.5h11A2.5 2.5 0 0 1 20 6v8a2.5 2.5 0 0 1-2.5 2.5H11L7 20v-3.5h-.5A2.5 2.5 0 0 1 4 14Z");
}

</style>
