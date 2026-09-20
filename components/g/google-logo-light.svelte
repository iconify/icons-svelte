<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b6oixc-gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:google-logo-light" {...props}></Icon>
<style>
:global(.b6oixc-gu) {
  fill: currentColor;
  d: path("M222 128a94 94 0 1 1-21.49-59.82a6 6 0 1 1-9.25 7.64A82 82 0 1 0 209.78 134H128a6 6 0 0 1 0-12h88a6 6 0 0 1 6 6");
}

</style>
