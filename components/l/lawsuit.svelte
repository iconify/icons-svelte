<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j13a13bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lawsuit" {...props}></Icon>
<style>
:global(.j13a13bsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.697 9.768l7.071-7.071l3.535 3.535l-7.071 7.071Zm7.053-.018L19 18M3 18h10v3.5H3Z");
}

</style>
