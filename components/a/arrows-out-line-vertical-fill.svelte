<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w04s-qvkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrows-out-line-vertical-fill" {...props}></Icon>
<style>
:global(.w04s-qvkg) {
  fill: currentColor;
  d: path("M88.61 51.06a8 8 0 0 1 1.73-8.72l32-32a8 8 0 0 1 11.32 0l32 32A8 8 0 0 1 160 56h-24v40a8 8 0 0 1-16 0V56H96a8 8 0 0 1-7.39-4.94M216 120H40a8 8 0 0 0 0 16h176a8 8 0 0 0 0-16m-56 80h-24v-40a8 8 0 0 0-16 0v40H96a8 8 0 0 0-5.66 13.66l32 32a8 8 0 0 0 11.32 0l32-32A8 8 0 0 0 160 200");
}

</style>
