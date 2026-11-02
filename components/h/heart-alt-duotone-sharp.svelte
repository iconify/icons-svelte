<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cgiq_22af"/><path class="xoycmbcij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-alt-duotone-sharp" {...props}></Icon>
<style>
:global(.cgiq_22af) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 6a4.242 4.242 0 1 1 6 6l-7 7l-7-7a4.242 4.242 0 1 1 6-6l1 1Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.xoycmbcij) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 7l1-1a4.243 4.243 0 0 1 6 6l-7 7l-7-7a4.243 4.243 0 0 1 6-6z");
}

</style>
