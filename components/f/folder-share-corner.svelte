<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4flo1ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-share-corner" {...props}></Icon>
<style>
:global(.vl4flo1ld) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5l2 2m4 8h4v4m0-4l-6 6");
}

</style>
