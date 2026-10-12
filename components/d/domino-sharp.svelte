<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ddoavgj8g"/><path class="m3fpj3xmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:domino-sharp" {...props}></Icon>
<style>
:global(.ddoavgj8g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.75h11v18.5h-11zm2 9.25h7");
}

:global(.m3fpj3xmp) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 5.5h.01M12 7.4h.01m2.49 1.9h.01M9.5 15h.01m4.99 0h.01M9.5 18.25h.01m4.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
