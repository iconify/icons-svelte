<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gspe7lvxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-off-round" {...props}></Icon>
<style>
:global(.gspe7lvxd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 16v-5a4 4 0 0 1 4-4h5m3 3v3a4 4 0 0 1-4 4h-3m1 0v4M9 3v4m6-4v4M2 20L20 2");
}

</style>
