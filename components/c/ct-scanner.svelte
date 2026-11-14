<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwy3ciu5d"/><path class="skti6bc6w"/><path class="lgs6j1bcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ct-scanner" {...props}></Icon>
<style>
:global(.jwy3ciu5d) {
  d: path("M2.5 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

:global(.lgs6j1bcf) {
  d: path("M9 9h12.5v2H9Zm9.5 2v10.5");
}

:global(.skti6bc6w) {
  d: path("m5 15l-1 6.5h10L13 15m-7-5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
