<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="hqze38a6p"/><path class="h4e08zb4z"/><path class="qfnbw8big"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:meme-frame-sharp" {...props}></Icon>
<style>
:global(.h4e08zb4z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 13.5l2.75-2.75l2 2l2.25-2.25l3 3");
}

:global(.hqze38a6p) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 6.75h9");
}

:global(.qfnbw8big) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17.25h10");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ywno-sh7h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
