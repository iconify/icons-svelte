<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0kdbnb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:retort-stand" {...props}></Icon>
<style>
:global(.o0kdbnb4q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 19h12v2.5h-12Zm3.5 0V2.5m0 5h7.5m0-3.5v10.5a2 2 0 0 0 4 0V4");
}

</style>
