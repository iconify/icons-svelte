<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cqz8_zmji"/><path class="h9qnlab5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:brownie-sharp" {...props}></Icon>
<style>
:global(.cqz8_zmji) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10.5L7 9l2.5 1L12 8.75l2.5 1L17 8.5l2.5 1.25V20.5h-15v-2Z");
}

:global(.h9qnlab5j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 14h.01m5.99-.75h.01M11.75 17h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
