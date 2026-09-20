<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zy52k8bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cookies-32-filled" {...props}></Icon>
<style>
:global(.zy52k8bmx) {
  fill: currentColor;
  d: path("M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14q0-.852-.1-1.68a1 1 0 0 0-1.75-.534a3.5 3.5 0 0 1-6.127-2.695a1 1 0 0 0-.89-1.11a3.5 3.5 0 0 1-2.032-6.03a1 1 0 0 0-.501-1.71A14 14 0 0 0 16 2m0 15.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M12.5 21a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M9 13.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M21.5 23a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
