<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ggl-zpb8v"/><path class="ot1rkkbxa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gift-receipt" {...props}></Icon>
<style>
:global(.ggl-zpb8v) {
  d: path("M3.5 2.5h17v18.75l-3.5-2l-3.5 2l-3.5-2l-3.5 2l-3-2Z");
}

:global(.ot1rkkbxa) {
  d: path("M12 10.5c-1.25-3.25-4.75-3.25-4.75-1s3.5 3 4.75 1Zm0 0c1.25-3.25 4.75-3.25 4.75-1s-3.5 3-4.75 1Zm-.75 2L9.5 16m3.25-3.5L14.5 16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
