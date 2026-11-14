<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ggmxwryuj"/><path class="zgmb3ck6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:railway-cutting" {...props}></Icon>
<style>
:global(.ggmxwryuj) {
  d: path("M3 21v-9a9 9 0 0 1 18 0v9M2.5 21h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zgmb3ck6d) {
  d: path("M7.5 9h9v10h-9Zm0 5.5h9");
}

</style>
