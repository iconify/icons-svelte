<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="wzlhpibsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-right-28-regular" {...props}></Icon>
<style>
:global(.wzlhpibsj) {
  fill: currentColor;
  d: path("M15.269 4.21a.75.75 0 0 0-1.04 1.08l8.274 7.96H3.75a.75.75 0 0 0 0 1.5h18.752l-8.273 7.959a.75.75 0 0 0 1.04 1.08l9.428-9.069a1 1 0 0 0 0-1.441z");
}

</style>
