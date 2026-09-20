<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="lpfj2qbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-28-regular" {...props}></Icon>
<style>
:global(.lpfj2qbmg) {
  fill: currentColor;
  d: path("M4.211 12.733a.75.75 0 1 0 1.081 1.04l7.96-8.275v18.753a.75.75 0 1 0 1.5 0V5.5l7.958 8.274a.75.75 0 0 0 1.081-1.04l-9.069-9.428a1 1 0 0 0-1.441 0z");
}

</style>
