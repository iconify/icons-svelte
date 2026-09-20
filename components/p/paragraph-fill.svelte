<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z8rar1fhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:paragraph-fill" {...props}></Icon>
<style>
:global(.z8rar1fhy) {
  fill: currentColor;
  d: path("M216 48a8 8 0 0 1-8 8h-16v152a8 8 0 0 1-16 0V56h-24v152a8 8 0 0 1-16 0v-40H96a64 64 0 0 1 0-128h112a8 8 0 0 1 8 8");
}

</style>
