<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9per0zpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-status-good-sharp" {...props}></Icon>
<style>
:global(.x9per0zpq) {
  fill: currentColor;
  d: path("M15.95 21.175L13.1 18.35l1.425-1.4l1.425 1.4l3.525-3.525l1.425 1.4zM7 22V4h3V2h4v2h3v8q-.2 0-.4.013t-.4.037q-2.2.3-3.7 1.975T11 18q0 1.125.4 2.15T12.525 22z");
}

</style>
