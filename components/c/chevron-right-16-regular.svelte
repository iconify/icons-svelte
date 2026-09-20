<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wm_su6btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-right-16-regular" {...props}></Icon>
<style>
:global(.wm_su6btw) {
  fill: currentColor;
  d: path("M5.646 3.146a.5.5 0 0 0 0 .708L9.793 8l-4.147 4.146a.5.5 0 0 0 .708.708l4.5-4.5a.5.5 0 0 0 0-.708l-4.5-4.5a.5.5 0 0 0-.708 0");
}

</style>
