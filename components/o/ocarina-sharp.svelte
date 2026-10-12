<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nf_erlgrf"/><path class="eovhpnbgi"/><path class="a1pbthbbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ocarina-sharp" {...props}></Icon>
<style>
:global(.a1pbthbbp) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 11.25h.01m3.24-1h.01m3.24 1h.01m-3.26 3.5h.01");
}

:global(.eovhpnbgi) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.15 10.75h-3.4v3.5h3.4");
}

:global(.nf_erlgrf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 12.5a7.75 5.5 0 1 0 15.5 0a7.75 5.5 0 1 0-15.5 0Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
