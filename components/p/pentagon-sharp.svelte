<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rm7kxw03f"/><path class="afk3glbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pentagon-sharp" {...props}></Icon>
<style>
:global(.afk3glbhf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01");
}

:global(.rm7kxw03f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.62 4.18l6.03 4.38l1.62 1.18l-.62 1.9l-2.3 7.1l-.62 1.9H6.27l-.62-1.9l-2.3-7.1l-.62-1.9l1.62-1.18l6.03-4.38L12 3z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
