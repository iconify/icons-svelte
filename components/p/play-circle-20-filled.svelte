<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fnb_6rbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:play-circle-20-filled" {...props}></Icon>
<style>
:global(.fnb_6rbyp) {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m6-2.167v4.334a.75.75 0 0 0 1.125.65l4.125-2.384a.5.5 0 0 0 0-.866L9.125 7.184A.75.75 0 0 0 8 7.834");
}

</style>
