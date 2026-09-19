<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hch983t8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-menu" {...props}></Icon>
<style>
:global(.hch983t8a) {
  fill: currentColor;
  d: path("M3 18h18v-2H3zm0-5h18v-2H3zm0-7v2h18V6z");
}

</style>
