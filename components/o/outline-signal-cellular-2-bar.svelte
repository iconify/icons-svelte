<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnumfnbbo"/><path class="vfica3t-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-signal-cellular-2-bar" {...props}></Icon>
<style>
:global(.mnumfnbbo) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M2 22h20V2z");
}

:global(.vfica3t-a) {
  fill: currentColor;
  d: path("M14 10L2 22h12z");
}

</style>
