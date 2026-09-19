<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a47ljxbek"/><circle class="uyhfztemm"/><circle class="een6afftk"/><circle class="ac2-8hbbw"/><path class="yp7tiudbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-sports-golf" {...props}></Icon>
<style>
:global(.a47ljxbek) {
  fill: currentColor;
  d: path("M12 16c3.87 0 7-3.13 7-7s-3.13-7-7-7s-7 3.13-7 7s3.13 7 7 7m0-12c2.76 0 5 2.24 5 5s-2.24 5-5 5s-5-2.24-5-5s2.24-5 5-5");
}

:global(.ac2-8hbbw) {
  cx: 12px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

:global(.een6afftk) {
  cx: 14px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

:global(.uyhfztemm) {
  cx: 10px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

:global(.yp7tiudbf) {
  fill: currentColor;
  d: path("M7 19h2c1.1 0 2 .9 2 2v1h2v-1c0-1.1.9-2 2-2h2v-2H7z");
}

</style>
