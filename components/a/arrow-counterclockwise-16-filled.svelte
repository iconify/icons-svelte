<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ykdnypp2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-counterclockwise-16-filled" {...props}></Icon>
<style>
:global(.ykdnypp2k) {
  fill: currentColor;
  d: path("M12.5 8a4.5 4.5 0 0 0-7.854-3H6.25a.75.75 0 0 1 0 1.5h-3a.75.75 0 0 1-.75-.75v-3a.75.75 0 1 1 1.5 0v.778a6 6 0 1 1-1.94 5.324a.75.75 0 1 1 1.485-.211A4.501 4.501 0 0 0 12.5 8");
}

</style>
