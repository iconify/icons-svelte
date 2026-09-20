<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r1i9n4f4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pipeline-32-filled" {...props}></Icon>
<style>
:global(.r1i9n4f4l) {
  fill: currentColor;
  d: path("M2 8a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0zm24 0a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0zm-2 1H8v14h16z");
}

</style>
