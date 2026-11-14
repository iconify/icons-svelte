<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzzibcbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:canyon-walls" {...props}></Icon>
<style>
:global(.jzzibcbnf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5v-17h3L7 9h1.25L10 20.5m11.5 0V6h-2.75l-1.5 5H16l-2 9.5m-11.5 0h19");
}

</style>
