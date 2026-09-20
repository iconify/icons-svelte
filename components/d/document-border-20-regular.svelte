<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ifwzp8bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-border-20-regular" {...props}></Icon>
<style>
:global(.ifwzp8bbn) {
  fill: currentColor;
  d: path("M6.5 2A2.5 2.5 0 0 0 4 4.5v11A2.5 2.5 0 0 0 6.5 18h7a2.5 2.5 0 0 0 2.5-2.5v-11A2.5 2.5 0 0 0 13.5 2zM5 4.5A1.5 1.5 0 0 1 6.5 3h7A1.5 1.5 0 0 1 15 4.5v11a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 5 15.5zM6.75 4a.75.75 0 0 0-.75.75v10.5c0 .414.336.75.75.75h6.5a.75.75 0 0 0 .75-.75V4.75a.75.75 0 0 0-.75-.75zM7 15V5h6v10z");
}

</style>
