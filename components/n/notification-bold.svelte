<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ni4j05b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notification-bold" {...props}></Icon>
<style>
:global(.ni4j05b7a) {
  fill: currentColor;
  d: path("M220 132v76a20 20 0 0 1-20 20H48a20 20 0 0 1-20-20V56a20 20 0 0 1 20-20h76a12 12 0 0 1 0 24H52v144h144v-72a12 12 0 0 1 24 0m16-72a40 40 0 1 1-40-40a40 40 0 0 1 40 40m-24 0a16 16 0 1 0-16 16a16 16 0 0 0 16-16");
}

</style>
