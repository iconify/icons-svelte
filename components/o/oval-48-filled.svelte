<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mns-w4bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-48-filled" {...props}></Icon>
<style>
:global(.mns-w4bba) {
  fill: currentColor;
  d: path("M4 24c0-8.284 6.716-15 15-15h10c8.284 0 15 6.716 15 15s-6.716 15-15 15H19c-8.284 0-15-6.716-15-15");
}

</style>
