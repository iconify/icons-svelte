<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="jvr028-8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-left-28-regular" {...props}></Icon>
<style>
:global(.jvr028-8e) {
  fill: currentColor;
  d: path("M24.78 3.22a.75.75 0 0 1 0 1.06L5.56 23.5h9.69a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75v-11.5a.75.75 0 0 1 1.5 0v9.69L23.72 3.22a.75.75 0 0 1 1.06 0");
}

</style>
