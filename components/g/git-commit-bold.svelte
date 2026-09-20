<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="t0pgdl8kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:git-commit-bold" {...props}></Icon>
<style>
:global(.t0pgdl8kx) {
  fill: currentColor;
  d: path("M244 116h-57.21a60 60 0 0 0-117.58 0H12a12 12 0 0 0 0 24h57.21a60 60 0 0 0 117.58 0H244a12 12 0 0 0 0-24m-116 48a36 36 0 1 1 36-36a36 36 0 0 1-36 36");
}

</style>
