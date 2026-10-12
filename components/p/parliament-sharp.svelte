<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y3awbccwx"/><path class="zj3mh0bhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parliament-sharp" {...props}></Icon>
<style>
:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.y3awbccwx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5H14v8.75H2.75zm3 3v3m2.75-3v3m2.75-3v3m2.75 2v-13l.38-.65l1.99-3.45l.38-.65l.38.65l1.99 3.45l.38.65v13.75H14z");
}

:global(.zj3mh0bhi) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 10.5h.01");
}

</style>
