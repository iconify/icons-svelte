<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ph5_p3bwd"/><path class="etv1o2b_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:joystick-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.etv1o2b_d) {
  d: path("M13 9.874V15a1 1 0 0 1-2 0V9.874a4 4 0 1 1 2 0M6 13a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Z");
}

:global(.ph5_p3bwd) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 17a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
