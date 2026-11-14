<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fwaqvoxfi"/><path class="v7mfnnboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:empty-nest" {...props}></Icon>
<style>
:global(.fwaqvoxfi) {
  d: path("M2.5 8.5h19c0 6-4.5 9.5-9.5 9.5s-9.5-3.5-9.5-9.5ZM4 6l3.5 2.5M20 6l-3.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v7mfnnboa) {
  d: path("m6 11.5l3 2.75l3-2.75l3 2.75l3-2.75");
}

</style>
