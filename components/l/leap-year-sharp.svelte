<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fiihs3-8t"/><path class="gnfs9sbpb"/><path class="fqf0oebvg"/><path class="spnbju8uc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:leap-year-sharp" {...props}></Icon>
<style>
:global(.fiihs3-8t) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.25h16.5v15H3.75zm0 4.75h16.5M8 2.75v4.5m8-4.5v4.5");
}

:global(.fqf0oebvg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 15a5.14 5.14 0 0 1 8.5 0");
}

:global(.gnfs9sbpb) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 17.75h.01");
}

:global(.spnbju8uc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 17.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
