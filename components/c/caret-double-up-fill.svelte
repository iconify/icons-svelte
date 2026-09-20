<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xu7hx9q4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-double-up-fill" {...props}></Icon>
<style>
:global(.xu7hx9q4l) {
  fill: currentColor;
  d: path("M213.66 194.34A8 8 0 0 1 208 208H48a8 8 0 0 1-5.66-13.66L108.69 128H48a8 8 0 0 1-5.66-13.66l80-80a8 8 0 0 1 11.32 0l80 80A8 8 0 0 1 208 128h-60.69Z");
}

</style>
