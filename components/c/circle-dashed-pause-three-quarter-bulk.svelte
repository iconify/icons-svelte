<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xu7tjvb8r"/><path class="rvtv2acwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-pause-three-quarter-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rvtv2acwz) {
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a10 10 0 0 1-9.877-11.564a1 1 0 1 1 1.975.313a8 8 0 1 0 6.651-6.651a1 1 0 1 1-.313-1.975A10 10 0 0 1 12 2M6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122A10 10 0 0 1 6.122 3.91");
}

:global(.xu7tjvb8r) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 15a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Z");
}

</style>
