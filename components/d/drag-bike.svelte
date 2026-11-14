<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ser4ni41n"/><path class="ldw6an86d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:drag-bike" {...props}></Icon>
<style>
:global(.ldw6an86d) {
  d: path("m6 13l5-4.5h5.5l2 4.5m-2-4.5l1-3M2.5 19h19");
}

:global(.ser4ni41n) {
  d: path("M3 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm12.5 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
