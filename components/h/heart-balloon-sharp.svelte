<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hv4rwfbhr"/><path class="i16t5qb-g"/><path class="pzhmyob9w"/><path class="tlcfuxave"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heart-balloon-sharp" {...props}></Icon>
<style>
:global(.hv4rwfbhr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.25c-4.5-3-7.75-5.75-7.75-9.25A4 4 0 0 1 12 5.5A4 4 0 0 1 19.75 7c0 3.5-3.25 6.25-7.75 9.25Z");
}

:global(.i16t5qb-g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 8l-.014-1.778L8.75 6");
}

:global(.pzhmyob9w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18h.01");
}

:global(.tlcfuxave) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 19l-1.5 1.125L12 21.25");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
