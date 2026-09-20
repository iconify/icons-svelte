<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hij7phbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-shape-up" {...props}></Icon>
<style>
:global(.hij7phbrp) {
  fill: currentColor;
  d: path("M8.539 20v-5.808H4L12 5l8 9.192h-4.538V20z");
}

</style>
