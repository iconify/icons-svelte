<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bgoap48rn"/><path class="x-_4otb8o"/><path class="r92h6ku6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bird-sharp" {...props}></Icon>
<style>
:global(.bgoap48rn) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 4.75h3.5V12c0 4.75-3.5 8.5-8.25 8.5H3.75l1.5-1.5v-2c0-4 2.75-6.75 6-7.25v-5zm3.75 2.5l2.75 1.25l-2.75 1.25Z");
}

:global(.r92h6ku6d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14.75h3.125L13.5 12.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x-_4otb8o) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 8h.01");
}

</style>
