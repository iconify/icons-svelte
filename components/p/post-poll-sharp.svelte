<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="g67wtabwr"/><path class="lmcw2zq3s"/><path class="s96vgdble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:post-poll-sharp" {...props}></Icon>
<style>
:global(.g67wtabwr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 8H14");
}

:global(.lmcw2zq3s) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.75 8l1 1l2-2");
}

:global(.s96vgdble) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12h5m-5 4H9");
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
