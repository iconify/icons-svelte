<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGfJiMjeNb"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="ysxp8xb2x"/><path class="p6ou3yb6v"/><path class="ei7ia5-jr"/><path class="hv0q1lgld"/><path class="w0lafwpwi"/></g></mask></defs><circle mask="url(#SVGfJiMjeNb)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:move-x-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ei7ia5-jr) {
  d: path("M19 13a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m-9.026 4.768a1 1 0 0 1-1.409-.128l-3.333-4a1 1 0 1 1 1.536-1.28l3.334 4a1 1 0 0 1-.128 1.408");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hv0q1lgld) {
  d: path("M9.974 8.232a1 1 0 0 1 .128 1.408l-3.334 4a1 1 0 1 1-1.536-1.28l3.333-4a1 1 0 0 1 1.409-.128");
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.kvn14gsjy) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

:global(.p6ou3yb6v) {
  d: path("M16.026 17.768a1 1 0 0 1-.128-1.408l3.334-4a1 1 0 1 1 1.536 1.28l-3.333 4a1 1 0 0 1-1.408.128");
}

:global(.w0lafwpwi) {
  d: path("M7 13a1 1 0 0 1 1-1h8a1 1 0 0 1 0 2H8a1 1 0 0 1-1-1");
}

:global(.ysxp8xb2x) {
  d: path("M16.026 8.232a1 1 0 0 1 1.409.128l3.333 4a1 1 0 1 1-1.536 1.28l-3.334-4a1 1 0 0 1 .128-1.408");
}

</style>
