<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rl0gwabzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-space-around-horizontal-20-filled" {...props}></Icon>
<style>
:global(.rl0gwabzi) {
  fill: currentColor;
  d: path("M6 4a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm0 7a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2z");
}

</style>
