<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nffs6d9du"/><path class="b6raz_3dy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:garage" {...props}></Icon>
<style>
:global(.b6raz_3dy) {
  d: path("M7 12.5h10v8H7Zm0 3h10M7 18h10");
}

:global(.nffs6d9du) {
  d: path("m3 11l9-7l9 7v9.5H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
