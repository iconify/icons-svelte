<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lxo8x4-rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:door-16-filled" {...props}></Icon>
<style>
:global(.lxo8x4-rg) {
  fill: currentColor;
  d: path("M3 3a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm3 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
