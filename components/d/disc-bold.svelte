<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="czrl5z9og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:disc-bold" {...props}></Icon>
<style>
:global(.czrl5z9og) {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m42.32 96a44 44 0 0 0-3.91-9.44l28.84-28.84A83.55 83.55 0 0 1 211.13 116ZM148 128a20 20 0 1 1-20-20a20 20 0 0 1 20 20m-20 84a84 84 0 1 1 50.28-151.25l-28.85 28.84A44 44 0 1 0 170.32 140h40.81A84.12 84.12 0 0 1 128 212");
}

</style>
