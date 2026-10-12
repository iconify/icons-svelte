<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yijeryb8x"/><path class="ikb95b_4o"/><path class="cq44-0b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:graphics-tablet-sharp" {...props}></Icon>
<style>
:global(.cq44-0b-z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 15.75l6.25-6.25");
}

:global(.ikb95b_4o) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9.5h.01m-.01 5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.yijeryb8x) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75zm4.5 0v14.5");
}

</style>
