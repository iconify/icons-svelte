<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ju3uevlhn"/><path class="qk-iuc4wi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-correlation-matrix" {...props}></Icon>
<style>
:global(.ju3uevlhn) {
  d: path("M3 3h18v18H3Zm6 0v18m6-18v18M3 9h18M3 15h18");
}

:global(.qk-iuc4wi) {
  fill: currentColor;
  d: path("M3 9V5a2 2 0 0 1 2-2h4v6Zm6 0h6v6H9Zm6 6h6v4a2 2 0 0 1-2 2h-4Zm-4.25-9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6 6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
