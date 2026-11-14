<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xvpzhc6sb"/><path class="na0rd0bej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mass-spectrometer" {...props}></Icon>
<style>
:global(.na0rd0bej) {
  d: path("M11.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xvpzhc6sb) {
  d: path("M6 6h15.5v12H6Zm-3.5 6H6");
}

</style>
