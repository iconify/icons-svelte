<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lzv0bnbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-left-simple-bold" {...props}></Icon>
<style>
:global(.lzv0bnbry) {
  fill: currentColor;
  d: path("M44 56v144a12 12 0 0 1-24 0V56a12 12 0 0 1 24 0m200 40v64a20 20 0 0 1-20 20H80a20 20 0 0 1-20-20V96a20 20 0 0 1 20-20h144a20 20 0 0 1 20 20m-24 4H84v56h136Z");
}

</style>
