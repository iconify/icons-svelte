<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG7RmJ4d1D"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="xjb8hnbhr"/><path class="nswx326bq"/><path class="lyij4hb_f"/><path class="bf9kdac0s"/><path class="zy-0nubnp"/></g></mask></defs><circle mask="url(#SVG7RmJ4d1D)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrows-spin-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.bf9kdac0s) {
  d: path("M9.349 9.969a1 1 0 0 1 1.11 1.664l-3.001 2a1 1 0 1 1-1.11-1.664z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ivjvz2eii) {
  fill: var(--svg-color--000, #000);
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.lyij4hb_f) {
  d: path("M21.832 15.445a1 1 0 0 1-1.664 1.11l-2-3a1 1 0 1 1 1.664-1.11zm-3.975-7.594a1 1 0 1 1-1.414 1.414a5 5 0 0 0-8.536 3.536a1 1 0 1 1-2 0a7 7 0 0 1 11.95-4.95");
}

:global(.nswx326bq) {
  d: path("M16.559 15.832a1 1 0 1 1-1.11-1.664l3-2a1 1 0 1 1 1.11 1.664z");
}

:global(.xjb8hnbhr) {
  d: path("M8.05 17.95a1 1 0 1 1 1.414-1.415A5 5 0 0 0 18 13a1 1 0 1 1 2 0a7 7 0 0 1-11.95 4.95");
}

:global(.zy-0nubnp) {
  d: path("M4.075 10.356a1 1 0 1 1 1.664-1.11l2 3a1 1 0 1 1-1.664 1.11z");
}

</style>
