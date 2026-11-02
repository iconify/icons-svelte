<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7ycqbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-fill-sharp" {...props}></Icon>
<style>
:global(.vn7ycqbrh) {
  fill: currentColor;
  d: path("M20 3a1 1 0 0 1 1 1v9c0 .265-.105.52-.293.707l-7 7A1 1 0 0 1 13 21H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm-7 10v6l6-6Z");
}

</style>
