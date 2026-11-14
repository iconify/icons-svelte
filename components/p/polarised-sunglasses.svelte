<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twug3cypx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:polarised-sunglasses" {...props}></Icon>
<style>
:global(.twug3cypx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h8v6.5h-8Zm11 0h8v6.5h-8Zm-3 2q1.5-1.5 3 0M5 13.5l3-3m8 3l3-3");
}

</style>
