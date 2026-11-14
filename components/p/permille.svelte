<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aifzpoajj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:permille" {...props}></Icon>
<style>
:global(.aifzpoajj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 19.5l10-15M3.75 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5.5 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM16 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
