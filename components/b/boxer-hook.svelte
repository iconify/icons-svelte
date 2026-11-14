<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pcwmoybnl"/><path class="s3bvbqbds"/><path class="dfzk7hzwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boxer-hook" {...props}></Icon>
<style>
:global(.dfzk7hzwq) {
  d: path("m15.75 15.25l2.75.75l1-2.75");
}

:global(.pcwmoybnl) {
  d: path("M3 13V8c0-2.75 2-4.5 4.5-4.5H9c2.75 0 4.5 2 4.5 4.75V13c0 1.5-1 2.5-2.5 2.5H5.5C4 15.5 3 14.5 3 13Zm1.5 2.5H12v5H4.5Z");
}

:global(.s3bvbqbds) {
  d: path("M3 10.5h3.5Q8 10.5 8 12m7.5-7.5C20 7 21 12 18.5 16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
