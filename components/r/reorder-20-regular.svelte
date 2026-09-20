<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="joqcrltoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:reorder-20-regular" {...props}></Icon>
<style>
:global(.joqcrltoq) {
  fill: currentColor;
  d: path("M2.5 8a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zm0 3a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
