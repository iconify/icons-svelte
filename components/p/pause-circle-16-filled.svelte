<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="psnkknbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pause-circle-16-filled" {...props}></Icon>
<style>
:global(.psnkknbvy) {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1M6.5 5a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5m3 0a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5");
}

</style>
