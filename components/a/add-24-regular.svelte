<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-ikozb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-24-regular" {...props}></Icon>
<style>
:global(.r-ikozb2b) {
  fill: currentColor;
  d: path("M12 3.25a.75.75 0 0 1 .75.75v7.25H20a.75.75 0 0 1 0 1.5h-7.25V20a.75.75 0 0 1-1.5 0v-7.25H4a.75.75 0 0 1 0-1.5h7.25V4a.75.75 0 0 1 .75-.75");
}

</style>
