<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9z6bcl7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-upload-16-filled" {...props}></Icon>
<style>
:global(.s9z6bcl7p) {
  fill: currentColor;
  d: path("M3.75 2a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm4.78 2.72a.75.75 0 0 0-1.06 0L4.22 7.97a.75.75 0 0 0 1.06 1.06l1.97-1.97v6.19a.75.75 0 0 0 1.5 0V7.06l1.97 1.97a.75.75 0 1 0 1.06-1.06z");
}

</style>
