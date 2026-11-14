<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zje8mu-nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lighting-tower" {...props}></Icon>
<style>
:global(.zje8mu-nf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h10V7H7ZM12 7v14.5m-5 0l5-6.5l5 6.5M6.5 9.75l-2 2.5m13-2.5l2 2.5");
}

</style>
