<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nzlcebc3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-half-fill-20-regular" {...props}></Icon>
<style>
:global(.nzlcebc3s) {
  fill: currentColor;
  d: path("M3 10a7 7 0 0 1 14 0zm7-8a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
