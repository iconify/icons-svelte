<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s59juobne"/><path class="nr1jsabyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:export-module" {...props}></Icon>
<style>
:global(.nr1jsabyh) {
  d: path("m3 10l7 3.5l1.318-.659m2.505-1.252L17 10m-7 3.5v8m2-12L19.5 2M15 2h4.5v4.5");
}

:global(.s59juobne) {
  d: path("M15.993 9.496L17 10v8l-7 3.5L3 18v-8l7-3.5l.716.358");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
