<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vyoj6947f"/><path class="j7w87kbrf"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:qr-label-sharp" {...props}></Icon>
<style>
:global(.j7w87kbrf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 14.25h-7v7Zm-15-8h3.5v3.5h-3.5Zm8 0h3.5v3.5h-3.5Zm-8 8h3.5v3.5h-3.5Z");
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vyoj6947f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h16.5v11.5l-7 7H2.75V2.75z");
}

</style>
