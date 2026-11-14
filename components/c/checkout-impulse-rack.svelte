<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k0l5g1bap"/><path class="xvguqcc_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:checkout-impulse-rack" {...props}></Icon>
<style>
:global(.k0l5g1bap) {
  d: path("M4 2.5h16v15H4Zm2.5 15v4m11-4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xvguqcc_h) {
  d: path("M7.5 5.5h3v9h-3Zm6 0h3v9h-3Z");
}

</style>
