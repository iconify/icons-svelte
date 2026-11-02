<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjsov3rpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-fill" {...props}></Icon>
<style>
:global(.cjsov3rpn) {
  fill: currentColor;
  d: path("M21 22H3a1 1 0 0 1 0-2h2V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v15h2a1 1 0 0 1 0 2m-6.99-11H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
