<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVG4LnKweXG" class="v8_uejvtn"/></defs><circle class="wu-xhbble"/><ellipse transform="rotate(-52.652 21.74 8.544)" class="p5-vn6bmk"/><path class="k91jfpdqw"/><path class="hn0360bcj"/><use href="#SVG4LnKweXG" class="c-zrgpb5l"/><path class="m68mexjju"/><use href="#SVG4LnKweXG" class="c-zrgpb5l"/><path class="eb5gck9mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:avenza" {...props}></Icon>
<style>
:global(.c-zrgpb5l) {
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.eb5gck9mo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.127 37.529l-3.773-3.335a.566.566 0 0 0-.77.02l-2.776 2.71l-.917-.91a.566.566 0 0 0-.795-.004l-2.323 2.273m4.035-1.358l1.532 1.497");
}

:global(.hn0360bcj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.908 32.579c2.847-.443 6.296.43 7.428 3.187a13.2 13.2 0 0 0 .84 2.513a3.375 3.375 0 0 0 3.357 1.928a6.74 6.74 0 0 1 4.592 1.705a3.9 3.9 0 0 1 1.02 1.618");
}

:global(.k91jfpdqw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.914 19.201v15.99m3.896-5.241c9.418.712 15.853 3.907 14.92 7.409s-8.934 6.182-18.552 6.215s-17.755-2.591-18.87-6.085s5.153-6.734 14.534-7.512");
}

:global(.m68mexjju) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.646 34.027c3.233-.25 7.17.593 8.178 3.98c.235 2.156 1.827 4.003 4.129 3.717a5.94 5.94 0 0 1 4.477 1.848");
}

:global(.p5-vn6bmk) {
  cx: 21.739px;
  cy: 8.544px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.631px;
  ry: 1.005px;
}

:global(.v8_uejvtn) {
  fill: none;
  stroke: currentColor;
  d: path("M27.81 29.95c9.418.712 15.853 3.907 14.92 7.409s-8.934 6.182-18.552 6.215s-17.755-2.591-18.87-6.085s5.153-6.734 14.534-7.512");
}

:global(.wu-xhbble) {
  cx: 24px;
  cy: 11.119px;
  r: 6.545px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
