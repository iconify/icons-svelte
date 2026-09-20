<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="q3d86q9xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-28-filled" {...props}></Icon>
<style>
:global(.q3d86q9xm) {
  fill: currentColor;
  d: path("M14 2C7.373 2 2 7.373 2 14s5.373 12 12 12s12-5.373 12-12S20.627 2 14 2m0 19.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15");
}

</style>
