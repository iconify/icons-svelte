<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zdhgclfwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-32-light" {...props}></Icon>
<style>
:global(.zdhgclfwi) {
  fill: currentColor;
  d: path("M29.854 5.146a.5.5 0 0 1 0 .708l-19 19a.5.5 0 0 1-.708 0l-8-8a.5.5 0 0 1 .708-.708l7.646 7.647L29.146 5.146a.5.5 0 0 1 .708 0");
}

</style>
