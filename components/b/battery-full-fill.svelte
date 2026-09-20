<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qszb1-o-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:battery-full-fill" {...props}></Icon>
<style>
:global(.qszb1-o-a) {
  fill: currentColor;
  d: path("M200 56H32A24 24 0 0 0 8 80v96a24 24 0 0 0 24 24h168a24 24 0 0 0 24-24V80a24 24 0 0 0-24-24m8 120a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V80a8 8 0 0 1 8-8h168a8 8 0 0 1 8 8Zm-16-80v64a8 8 0 0 1-8 8H48a8 8 0 0 1-8-8V96a8 8 0 0 1 8-8h136a8 8 0 0 1 8 8m64 0v64a8 8 0 0 1-16 0V96a8 8 0 0 1 16 0");
}

</style>
