<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fg7v7o45s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:paperclip-horizontal-light" {...props}></Icon>
<style>
:global(.fg7v7o45s) {
  fill: currentColor;
  d: path("M246 128a54.06 54.06 0 0 1-54 54H48a38 38 0 0 1 0-76h144a22 22 0 0 1 0 44H80a6 6 0 0 1 0-12h112a10 10 0 0 0 0-20H48a26 26 0 0 0 0 52h144a42 42 0 0 0 0-84H80a6 6 0 0 1 0-12h112a54.06 54.06 0 0 1 54 54");
}

</style>
