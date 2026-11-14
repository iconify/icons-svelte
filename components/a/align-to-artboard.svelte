<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvr-uoklt"/><path class="ajmeehv7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:align-to-artboard" {...props}></Icon>
<style>
:global(.ajmeehv7u) {
  d: path("M5.5 5.5h6v6h-6Z");
}

:global(.fvr-uoklt) {
  d: path("M5.5 2.5v19m-3-16h19m-16 0h15v15h-15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
