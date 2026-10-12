<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cim1a2bwc"/><path class="jddzqsu_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:border-inner-sharp" {...props}></Icon>
<style>
:global(.cim1a2bwc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h.01M3 7.5h.01m-.01 9h.01M3 21h.01M7.5 3h.01M7.5 21h.01M16.5 3h.01m-.01 18h.01M21 3h.01M21 7.5h.01m-.01 9h.01M21 21h.01");
}

:global(.jddzqsu_d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v18m-9-9h18");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
