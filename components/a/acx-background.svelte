<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="lp4784brz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:acx-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lp4784brz) {
  fill: var(--svg-color--6cf9d7, #6cf9d7);
  d: path("M9.92 11.525L4 5.605L5.605 4l5.92 5.92a2.13 2.13 0 0 0-1.605 1.605m2.555-1.605a2.13 2.13 0 0 1 1.605 1.605L20 5.605L18.395 4zm1.605 2.555a2.13 2.13 0 0 1-1.605 1.605l5.92 5.92L20 18.395zm-2.555 1.605L5.605 20L4 18.395l5.92-5.92a2.13 2.13 0 0 0 1.605 1.605");
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
