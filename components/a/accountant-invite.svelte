<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh6bzhbbg"/><path class="i0x91lukr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:accountant-invite" {...props}></Icon>
<style>
:global(.i0x91lukr) {
  d: path("m2.5 6l9 5.5l9-5.5M18 14.5v7M14.5 18h7");
}

:global(.oh6bzhbbg) {
  d: path("M11.7 17H2.5V3.5h18v8.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
