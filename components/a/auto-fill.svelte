<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoemnwpzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:auto-fill" {...props}></Icon>
<style>
:global(.xoemnwpzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.1 21.5H4v-19h15v7.7m0 10.2v1.1h-1.1M7.5 7.5h8m-8 4.5H13m1 9.5l3.75-3.75M20 13v3m-1.5-1.5h3");
}

</style>
