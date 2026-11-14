<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="raqkqzbql"/><path class="a6d3czbst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:first-week-plan" {...props}></Icon>
<style>
:global(.a6d3czbst) {
  d: path("m16.5 16l2 2l-2 2");
}

:global(.raqkqzbql) {
  d: path("M13.6 21H3.5V4.5h17v7.2M8 2.5v4m8-4v4m-12.5 3h17m-2 5h1.75a1.25 1.25 0 0 1 1.25 1.25v4.5a1.25 1.25 0 0 1-1.25 1.25H18.5M13.75 18h4.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
