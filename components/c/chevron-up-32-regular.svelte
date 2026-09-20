<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ddwhpcbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-up-32-regular" {...props}></Icon>
<style>
:global(.ddwhpcbzl) {
  fill: currentColor;
  d: path("M5.293 20.707a1 1 0 0 0 1.414 0L16 11.414l9.293 9.293a1 1 0 0 0 1.414-1.414l-10-10a1 1 0 0 0-1.414 0l-10 10a1 1 0 0 0 0 1.414");
}

</style>
