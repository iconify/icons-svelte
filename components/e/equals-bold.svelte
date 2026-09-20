<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iiu4r_vok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:equals-bold" {...props}></Icon>
<style>
:global(.iiu4r_vok) {
  fill: currentColor;
  d: path("M228 160a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h176a12 12 0 0 1 12 12M40 108h176a12 12 0 0 0 0-24H40a12 12 0 0 0 0 24");
}

</style>
