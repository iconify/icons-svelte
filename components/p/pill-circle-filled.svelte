<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGFzABVc2e"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="ag8j2ab1q"/></mask></defs><circle mask="url(#SVGFzABVc2e)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:pill-circle-filled" {...props}></Icon>
<style>
:global(.ag8j2ab1q) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m13.546 7.182l6.364 6.364a4.5 4.5 0 1 1-6.364 6.364l-6.364-6.364a4.5 4.5 0 1 1 6.364-6.364M16 12.5q-1-1-2.5-.5t-2 3l3.42 3.444l.006.006c.973.973 2.55.973 3.524 0l.007-.008a2.49 2.49 0 0 0-.015-3.52z");
}

:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
