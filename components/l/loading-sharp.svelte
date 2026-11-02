<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxt7g3rhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:loading-sharp" {...props}></Icon>
<style>
:global(.yxt7g3rhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12-4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-6 2a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
