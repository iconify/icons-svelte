<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv08vkb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:milk-carton" {...props}></Icon>
<style>
:global(.cv08vkb3a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9L9 4h6l3.5 5v10a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2Zm0 0h13M9 4v5");
}

</style>
