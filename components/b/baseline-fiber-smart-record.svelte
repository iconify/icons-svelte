<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="z59go1_xr"/><path class="h0bn7_biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-fiber-smart-record" {...props}></Icon>
<style>
:global(.h0bn7_biy) {
  fill: currentColor;
  d: path("M17 4.26v2.09a5.99 5.99 0 0 1 0 11.3v2.09c3.45-.89 6-4.01 6-7.74s-2.55-6.85-6-7.74");
}

:global(.z59go1_xr) {
  cx: 9px;
  cy: 12px;
  r: 8px;
  fill: currentColor;
}

</style>
