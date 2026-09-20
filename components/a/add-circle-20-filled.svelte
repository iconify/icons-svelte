<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xta5jsbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-circle-20-filled" {...props}></Icon>
<style>
:global(.xta5jsbqr) {
  fill: currentColor;
  d: path("M18 10a8 8 0 1 1-16 0a8 8 0 0 1 16 0M6 10a.5.5 0 0 0 .5.5h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0-.5.5");
}

</style>
