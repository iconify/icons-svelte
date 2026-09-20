<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG5D2CyGoG"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="fo_2hkbcs"/></mask></defs><circle mask="url(#SVG5D2CyGoG)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:line-y-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.fo_2hkbcs) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M13 4a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V5a1 1 0 0 1 1-1");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
