<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="gyni5f9dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:person-28-filled" {...props}></Icon>
<style>
:global(.gyni5f9dp) {
  fill: currentColor;
  d: path("M21 16a3 3 0 0 1 3 3v.715C24 23.292 19.79 26 14 26S4 23.433 4 19.715V19a3 3 0 0 1 3-3zM14 2a6 6 0 1 1 0 12a6 6 0 0 1 0-12");
}

</style>
