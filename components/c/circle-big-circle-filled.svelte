<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG3iWrYbMa"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="ar35q0qfc"/></mask></defs><circle mask="url(#SVG3iWrYbMa)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:circle-big-circle-filled" {...props}></Icon>
<style>
:global(.ar35q0qfc) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M13 5.5a7.5 7.5 0 1 0 0 15a7.5 7.5 0 0 0 0-15M3.5 13a9.5 9.5 0 1 1 19 0a9.5 9.5 0 0 1-19 0");
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
