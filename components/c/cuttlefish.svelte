<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogt08tq-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cuttlefish" {...props}></Icon>
<style>
:global(.ogt08tq-c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 8.5q-2.5-2.75-5-.75q-2.5-2-5 0C3.5 8.25 2.5 10 2.5 12s1 3.75 3.5 4.25q2.5 2 5 0q2.5 2 5-.75Zm0 1.25c2.5 0 3.5-1.25 5.5-1M16 12h5.5M16 14.25c2.5 0 3.5 1.25 5.5 1m-8.5-4.5h.01");
}

</style>
