<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="goc8j7ehc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-line-up-left-thin" {...props}></Icon>
<style>
:global(.goc8j7ehc) {
  fill: currentColor;
  d: path("M228 208a4 4 0 0 1-4 4H48a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4M72 148a4 4 0 0 0 4-4V57.66l105.17 105.17a4 4 0 0 0 5.66-5.66L81.66 52H168a4 4 0 0 0 0-8H72a4 4 0 0 0-4 4v96a4 4 0 0 0 4 4");
}

</style>
