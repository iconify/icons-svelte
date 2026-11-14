<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vtb9yywnl"/><path class="tc3bcib6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kitchen-shop" {...props}></Icon>
<style>
:global(.tc3bcib6n) {
  d: path("M6 14.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 0h4.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vtb9yywnl) {
  d: path("m3 9l9-6.5L21 9v12.5H3Z");
}

</style>
