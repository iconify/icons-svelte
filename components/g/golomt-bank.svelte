<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="waxfmcr-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:golomt-bank" {...props}></Icon>
<style>
:global(.waxfmcr-o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.234 31l6.28-14H44.31a21.5 21.5 0 1 0 0 14H28.523");
}

</style>
