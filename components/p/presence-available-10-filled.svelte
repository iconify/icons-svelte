<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="t80um-b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-available-10-filled" {...props}></Icon>
<style>
:global(.t80um-b-c) {
  fill: currentColor;
  d: path("M5 10A5 5 0 1 0 5 0a5 5 0 0 0 0 10m2.104-5.896l-2.25 2.25a.5.5 0 0 1-.708 0l-1-1a.5.5 0 0 1 .708-.708l.646.647l1.896-1.897a.5.5 0 0 1 .708.708");
}

</style>
