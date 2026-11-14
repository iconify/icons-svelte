<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdbaq4zmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:detonating-cord" {...props}></Icon>
<style>
:global(.jdbaq4zmw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h11m5 0h3m-3.75 1.75L20 16m-4-1.5v3m-1.75-3.75L12 16m2.25-5.75L12 8m4 1.5v-3m1.75 3.75L20 8");
}

</style>
