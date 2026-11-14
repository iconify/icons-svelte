<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf703vb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:casual-attire" {...props}></Icon>
<style>
:global(.uf703vb9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5q3 3 6 0L21.5 7l-2 4.5l-2-1v10h-11v-10l-2 1l-2-4.5ZM6.5 5v5.5m11-5.5v5.5");
}

</style>
