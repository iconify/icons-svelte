<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afrcktbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:pause" {...props}></Icon>
<style>
:global(.afrcktbrk) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 17.75V6.25q0-3-3-3t-3 3v11.5q0 1.243.879 2.121q.878.879 2.121.879t2.121-.879q.879-.878.879-2.121m2.5-11.5q0-3 3-3t3 3v11.5q0 1.243-.879 2.121q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121z");
}

</style>
