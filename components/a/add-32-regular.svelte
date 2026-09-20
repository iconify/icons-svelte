<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1gprpc3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-32-regular" {...props}></Icon>
<style>
:global(.m1gprpc3n) {
  fill: currentColor;
  d: path("M16 3a1 1 0 0 1 1 1v11h11a1 1 0 1 1 0 2H17v11a1 1 0 1 1-2 0V17H4a1 1 0 1 1 0-2h11V4a1 1 0 0 1 1-1");
}

</style>
