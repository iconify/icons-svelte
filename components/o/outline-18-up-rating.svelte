<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbpapnofc"/><path class="bn6ebpb5p"/><path class="jj_ogub1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-18-up-rating" {...props}></Icon>
<style>
:global(.bbpapnofc) {
  fill: currentColor;
  d: path("M8.5 15H10V9H7v1.5h1.5z");
}

:global(.bn6ebpb5p) {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

:global(.jj_ogub1m) {
  fill: currentColor;
  d: path("M12.5 15H15c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1h-2.5c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1m.5-5h1.5v1.5H13zm0 2.5h1.5V14H13z");
}

</style>
