<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jfrb4ob6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-kzt-bold" {...props}></Icon>
<style>
:global(.jfrb4ob6j) {
  fill: currentColor;
  d: path("M212 100a12 12 0 0 1-12 12h-60v100a12 12 0 0 1-24 0V112H56a12 12 0 0 1 0-24h144a12 12 0 0 1 12 12M56 64h144a12 12 0 0 0 0-24H56a12 12 0 0 0 0 24");
}

</style>
