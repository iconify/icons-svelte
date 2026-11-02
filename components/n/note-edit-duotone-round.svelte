<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ip84-2sbm"/><path class="cxwa6gl-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-edit-duotone-round" {...props}></Icon>
<style>
:global(.cxwa6gl-p) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 4H8a4 4 0 0 0-4 4v8a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4v-3M9 15v-3l9-9l3 3l-9 9Zm6-9l3 3");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ip84-2sbm) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 15v-3l9-9l3 3l-9 9Z");
}

</style>
