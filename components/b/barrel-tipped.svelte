<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l2tu2emwx"/><path class="tw3ss488w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:barrel-tipped" {...props}></Icon>
<style>
:global(.l2tu2emwx) {
  d: path("M16 4H6.5c-2.5 0-4 2.5-4 5s1.5 5 4 5H16");
}

:global(.tw3ss488w) {
  d: path("M13.5 9a2.5 5 0 1 0 5 0a2.5 5 0 1 0-5 0ZM7 4v10m3.5-10v10m.5 5a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
