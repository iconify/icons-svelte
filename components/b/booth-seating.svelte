<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h9p_uac7a"/><path class="pbr_27bhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:booth-seating" {...props}></Icon>
<style>
:global(.h9p_uac7a) {
  d: path("M4 17V9c0-2.5 2-4 4-4h8c2 0 4 1.5 4 4v8");
}

:global(.pbr_27bhi) {
  d: path("M4 12h16v5H4Zm2 8.5V17m12 3.5V17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
