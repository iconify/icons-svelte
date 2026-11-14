<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8k2d7-4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:home-plate" {...props}></Icon>
<style>
:global(.d8k2d7-4k) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 2.75H5.75q-1.036 0-1.768.732T3.25 5.25v6.525q0 1.036.733 1.768l6.25 6.251q1.767 1.765 3.534-.001l6.25-6.249q.733-.733.733-1.769V5.25q0-1.036-.732-1.768T18.25 2.75M9 6.25h6q2.25 0 2.25 2.25v2.379q0 .931-.658 1.59l-3.001 3q-.659.66-1.591.66t-1.591-.66l-3-3q-.659-.659-.659-1.59V8.5q0-2.25 2.25-2.25");
}

</style>
