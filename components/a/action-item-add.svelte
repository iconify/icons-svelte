<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y9gvcmbly"/><path class="ne9-c3blp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:action-item-add" {...props}></Icon>
<style>
:global(.ne9-c3blp) {
  d: path("m5.5 8.5l1.75 1.75L9.75 7m5.75 1.5h6M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9gvcmbly) {
  d: path("M2.5 3.5h10v10h-10Z");
}

</style>
