<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q_x-ecb9w"/><path class="e8nj4k-iu"/><path class="fmt7gtbnv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:printer-sharp" {...props}></Icon>
<style>
:global(.e8nj4k-iu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 13.25h10.5v8H6.75z");
}

:global(.fmt7gtbnv) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 11h.01");
}

:global(.q_x-ecb9w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17.25h-4v-9.5h18.5v9.5h-4m-10.5-9.5v-5h10.5v5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
