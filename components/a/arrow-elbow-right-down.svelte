<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ux1j7mb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-right-down" {...props}></Icon>
<style>
:global(.ux1j7mb4l) {
  fill: currentColor;
  d: path("m229.66 165.66l-48 48a8 8 0 0 1-11.32 0l-48-48a8 8 0 0 1 11.32-11.32L168 188.69V72H32a8 8 0 0 1 0-16h144a8 8 0 0 1 8 8v124.69l34.34-34.35a8 8 0 0 1 11.32 11.32");
}

</style>
