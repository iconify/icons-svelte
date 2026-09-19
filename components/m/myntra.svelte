<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-68.92 28.311 24)" class="pwdsflbmw"/><path class="nj8_5n-wn"/><ellipse transform="rotate(-68.92 10.856 24)" class="mt5o01w_f"/><path class="y2gtxfqhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myntra" {...props}></Icon>
<style>
:global(.mt5o01w_f) {
  cx: 10.856px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.871px;
  ry: 4.22px;
}

:global(.nj8_5n-wn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.727 24.215q.227.647.48 1.303c2.756 7.148 6.752 12.263 8.927 11.425s1.703-7.312-1.052-14.46s-6.752-12.264-8.927-11.426");
}

:global(.pwdsflbmw) {
  cx: 28.311px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.871px;
  ry: 4.22px;
}

:global(.y2gtxfqhs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.272 24.215q.227.647.48 1.303c2.06 5.343 4.812 9.55 6.98 10.984M24 23.49q-.18-.501-.374-1.008c-2.756-7.148-6.752-12.263-8.927-11.425");
}

</style>
