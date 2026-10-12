<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o_vo1ib2r"/><path class="izangtb6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:assembly-line-sharp" {...props}></Icon>
<style>
:global(.izangtb6s) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 18.75h.01m11.99 0h.01");
}

:global(.o_vo1ib2r) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 2.75v3m-2 0h4m-14 3h5v4.5h-5zm9.5 0h5v4.5h-5zm-11.5 7.5h18.5v5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
