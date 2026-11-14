<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y7plm2b4h"/><path class="h2qmzccue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:click-tracking" {...props}></Icon>
<style>
:global(.h2qmzccue) {
  d: path("M14.5 14.5h3.75l3.5 3.5L18 21.75l-3.5-3.5Zm2.25 2.25h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y7plm2b4h) {
  d: path("M11.723 13.948L10 19.5L3.5 3L19 10l-5.211 1.737");
}

</style>
