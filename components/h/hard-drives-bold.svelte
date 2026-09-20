<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m3xqg6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:hard-drives-bold" {...props}></Icon>
<style>
:global(.m3xqg6bjn) {
  fill: currentColor;
  d: path("M208 36H48a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 24v56H52V60ZM52 196v-56h152v56ZM160 88a16 16 0 1 1 16 16a16 16 0 0 1-16-16m32 80a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
