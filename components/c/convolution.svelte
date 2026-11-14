<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e2h9i4bpl"/><path class="xkny57b_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:convolution" {...props}></Icon>
<style>
:global(.e2h9i4bpl) {
  d: path("M10 17.5H4.5a2 2 0 0 1-2-2v-11a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2V10m-10-7.5v15m5-15V10m-10-2.5h15m-15 5H10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xkny57b_l) {
  d: path("M10 10h10v10H10Z");
}

</style>
