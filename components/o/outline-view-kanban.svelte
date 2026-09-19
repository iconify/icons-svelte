<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfoe2vb2f"/><path class="bn6ebpb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-view-kanban" {...props}></Icon>
<style>
:global(.bn6ebpb5p) {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

:global(.rfoe2vb2f) {
  fill: currentColor;
  d: path("M7 7h2v10H7zm4 0h2v5h-2zm4 0h2v8h-2z");
}

</style>
