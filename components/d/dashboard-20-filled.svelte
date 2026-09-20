<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m4ng9jbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dashboard-20-filled" {...props}></Icon>
<style>
:global(.m4ng9jbhi) {
  fill: currentColor;
  d: path("M7 17H6a3 3 0 0 1-3-3v-1h4zm10-3a3 3 0 0 1-3 3H8v-4h9zm-5-2H3V6a3 3 0 0 1 3-3h6zm5 0h-4V8h4zm-3-9a3 3 0 0 1 3 3v1h-4V3z");
}

</style>
