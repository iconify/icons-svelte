<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0jzrhf-f"/><path class="yxb-yihdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:matte-painting" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v0jzrhf-f) {
  d: path("M12.7 17.5H2.5v-14H20v8.1");
}

:global(.yxb-yihdi) {
  d: path("m6 14.5l4-4.5l4.5 4.5M14 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5 7.5L20 18l-2.5 2.5c-1 1-3 1-3 1s0-2 1-3Zm1.25 1.25l3-3");
}

</style>
