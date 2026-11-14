<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkvy0yb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:headphones-check" {...props}></Icon>
<style>
:global(.zkvy0yb4f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5v-1a7 7 0 0 1 14 0v1m-16 0h5v7H3Zm13 0h5v7h-5ZM10 16l1.5 1.5L14 15");
}

</style>
