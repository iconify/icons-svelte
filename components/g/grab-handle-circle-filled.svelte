<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGmhRzfUna"><path class="k5-vjlrin"/><path class="slgbpticm"/></mask></defs><circle mask="url(#SVGmhRzfUna)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:grab-handle-circle-filled" {...props}></Icon>
<style>
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

:global(.slgbpticm) {
  fill: var(--svg-color--000, #000);
  d: path("M5.5 11a1 1 0 0 1 0-2h15a1 1 0 1 1 0 2zm0 3.25a1 1 0 1 1 0-2h15a1 1 0 1 1 0 2zm0 3.25a1 1 0 1 1 0-2h15a1 1 0 1 1 0 2z");
}

</style>
