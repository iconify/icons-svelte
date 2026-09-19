<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av4yvccls"/><path class="hmo41kyjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-home-work" {...props}></Icon>
<style>
:global(.av4yvccls) {
  fill: currentColor;
  d: path("M1 11v10h6v-5h2v5h6V11L8 6zm12 8h-2v-5H5v5H3v-6.97l5-3.57l5 3.57zm4-12h2v2h-2zm0 4h2v2h-2zm0 4h2v2h-2z");
}

:global(.hmo41kyjx) {
  fill: currentColor;
  d: path("M10 3v1.97l2 1.43V5h9v14h-4v2h6V3z");
}

</style>
