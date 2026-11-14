<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wge7tfb_u"/><path class="stv3xrboj"/><path class="lsahrw0eu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:childrens-ward" {...props}></Icon>
<style>
:global(.lsahrw0eu) {
  d: path("M11 12.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Z");
}

:global(.stv3xrboj) {
  fill: currentColor;
  d: path("M11 6.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3.5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wge7tfb_u) {
  d: path("M3 4v16.5m0-6h18v6M3 18h18M11.5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
