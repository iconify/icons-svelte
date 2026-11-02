<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az078c_gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-check-fill-round" {...props}></Icon>
<style>
:global(.az078c_gz) {
  fill: currentColor;
  d: path("M11 2h6a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5h-6a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m.707 7.293a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414L13 10.586ZM4 9v8a3 3 0 0 0 3 3h8a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V9a1 1 0 0 1 2 0");
}

</style>
