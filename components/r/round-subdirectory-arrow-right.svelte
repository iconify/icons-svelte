<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ane-7e00d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-subdirectory-arrow-right" {...props}></Icon>
<style>
:global(.ane-7e00d) {
  fill: currentColor;
  d: path("m18.29 15.71l-4.58 4.58c-.39.39-1.03.39-1.42 0s-.39-1.03 0-1.42L15.17 16H5c-.55 0-1-.45-1-1V5c0-.55.45-1 1-1s1 .45 1 1v9h9.17l-2.88-2.87c-.39-.39-.39-1.03 0-1.42s1.03-.39 1.42 0l4.58 4.58c.39.39.39 1.03 0 1.42");
}

</style>
