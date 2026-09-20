<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d1ay-abod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dust-20-filled" {...props}></Icon>
<style>
:global(.d1ay-abod) {
  fill: currentColor;
  d: path("M5.75 3.5a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m2.34 2.652A4.001 4.001 0 1 1 14.646 10a4 4 0 1 1-6.556 3.85a4 4 0 1 1 0-7.699M5.75 18a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M19 10a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

</style>
