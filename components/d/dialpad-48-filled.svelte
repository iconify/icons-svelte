<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bahdv8jzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dialpad-48-filled" {...props}></Icon>
<style>
:global(.bahdv8jzm) {
  fill: currentColor;
  d: path("M13.5 11.5a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6m10.5-20a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6m10.5-30a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0 10a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
