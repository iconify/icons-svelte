<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov_ptmbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-fill-round" {...props}></Icon>
<style>
:global(.ov_ptmbpf) {
  fill: currentColor;
  d: path("M16 9a5 5 0 0 1 5 5v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-3a5 5 0 0 1 5-5V6a4 4 0 0 1 8 0Zm-2 0V6a2 2 0 1 0-4 0v3Z");
}

</style>
