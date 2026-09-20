<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="spx89f_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bag-simple-bold" {...props}></Icon>
<style>
:global(.spx89f_wv) {
  fill: currentColor;
  d: path("M216 60h-36.17a52 52 0 0 0-103.66 0H40a20 20 0 0 0-20 20v120a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V80a20 20 0 0 0-20-20m-88-24a28 28 0 0 1 27.71 24h-55.42A28 28 0 0 1 128 36m84 160H44V84h168Z");
}

</style>
