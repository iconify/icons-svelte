<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au1kicbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:photo-library" {...props}></Icon>
<style>
:global(.au1kicbxi) {
  fill: currentColor;
  d: path("M22 16V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2m-11-4l2.03 2.71L16 11l4 5H8zM2 6v14c0 1.1.9 2 2 2h14v-2H4V6z");
}

</style>
