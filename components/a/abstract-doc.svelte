<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s7z1mzabd"/><path class="g5k3bk1ge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:abstract-doc" {...props}></Icon>
<style>
:global(.g5k3bk1ge) {
  d: path("M14 2.5v5h5m-11 4h8M8 15h8m-8 3.5h4.5");
}

:global(.s7z1mzabd) {
  d: path("M5 2.5h9l5 5v14H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
