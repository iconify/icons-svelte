<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f6v0-0b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-short-20-regular" {...props}></Icon>
<style>
:global(.f6v0-0b3r) {
  fill: currentColor;
  d: path("M9.5 3a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-1 0v-13a.5.5 0 0 1 .5-.5");
}

</style>
