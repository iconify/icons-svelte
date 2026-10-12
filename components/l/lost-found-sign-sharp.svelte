<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="t5ln1xa7a"/><path class="wu8tkc12a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lost-found-sign-sharp" {...props}></Icon>
<style>
:global(.t5ln1xa7a) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 11a3.75 3.75 0 0 1 7.5 0Zm3.75 0v6h-2v-1M14 9.5a1.75 1.75 0 1 1 2.5 1.6l-.75.375v1.775");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wu8tkc12a) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 16h.01");
}

:global(.ywno-sh7h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
