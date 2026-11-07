<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu_zjcw1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-off" {...props}></Icon>
<style>
:global(.zu_zjcw1r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2m6 0h8a2 2 0 0 1 2 2v8m-2 4h-7m4-9l4-4M2 2l20 20");
}

</style>
