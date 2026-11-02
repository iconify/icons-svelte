<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpj8x5bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:podcast" {...props}></Icon>
<style>
:global(.tpj8x5bzh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v8m-4-6a5 5 0 1 1 8 0M3 12a9 9 0 0 1 18 0");
}

</style>
