<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z9al01-fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-left-20-filled" {...props}></Icon>
<style>
:global(.z9al01-fg) {
  fill: currentColor;
  d: path("M12 16.25a.75.75 0 0 1-.75.75h-7.5a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 1 1 1.5 0v5.69L15.72 3.22a.75.75 0 1 1 1.06 1.06L5.56 15.5h5.69a.75.75 0 0 1 .75.75");
}

</style>
