<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bp86oyaez"/><path class="xnjprmbiw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pin-duotone-sharp" {...props}></Icon>
<style>
:global(.bp86oyaez) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 3h8a2 2 0 1 1 0 4a1 1 0 0 0-1 1v3c.004 2.018 3.996 1.982 4 4v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1c.004-2.018 3.996-1.982 4-4V8a1 1 0 0 0-1-1a2 2 0 1 1 0-4");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.xnjprmbiw) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4a2 2 0 1 1 0 4a1 1 0 0 0-1 1v3c0 2 4 2 4 4v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1c0-2 4-2 4-4V8a1 1 0 0 0-1-1a2 2 0 1 1 0-4Zm0 14v4");
}

</style>
