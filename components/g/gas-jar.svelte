<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cic9bggnc"/><path class="k3a74xbtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gas-jar" {...props}></Icon>
<style>
:global(.cic9bggnc) {
  d: path("M5.5 3H7v16.5a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V3h1.5");
}

:global(.k3a74xbtr) {
  d: path("M9.75 13a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
