<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wtdect0gn"/><path class="vfsl79b9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mountain-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.vfsl79b9w) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l2-4a1.118 1.118 0 0 1 2 0l1 2a1.118 1.118 0 0 0 2 0a1.118 1.118 0 0 1 2 0l3 6c.919 1.838-.162 4-2 4H7c-1.838 0-2.919-2.162-2-4z");
}

:global(.wtdect0gn) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 7a1.118 1.118 0 0 1 2 0l1 2a1.118 1.118 0 0 0 2 0a1.118 1.118 0 0 1 2 0l3 6c.919 1.838-.162 4-2 4H7c-1.838 0-2.919-2.162-2-4Z");
}

</style>
