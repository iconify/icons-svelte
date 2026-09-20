<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hll2hh7_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-left-20-filled" {...props}></Icon>
<style>
:global(.hll2hh7_x) {
  fill: currentColor;
  d: path("M15 4a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zM8.5 15H15a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2H8.5z");
}

</style>
