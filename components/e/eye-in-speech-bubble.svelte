<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG5SEmMbgE" class="ltg6mtw2c"/></defs><g class="n1mjunbsu"><use href="#SVG5SEmMbgE" class="xyjtgccot"/><path class="sv1djk37v"/></g><circle class="yxosv3w1o"/><circle class="l757vdbkr"/><circle class="zdj3g7b2z"/><g class="ft5dv1b6b"><use href="#SVG5SEmMbgE" class="xyjtgccot"/><path class="iz66a5byq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto:eye-in-speech-bubble" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iz66a5byq) {
  stroke: var(--svg-color--000, #000);
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M104.36 88.48a60.53 60.53 0 0 0 19.78-27.21S109.95 20 64.73 20S5 61.27 5 61.27s12.42 39.85 59.73 39.85c7.34.06 14.64-1.02 21.64-3.21c6 8.49 18.78 12.47 25.3 13.33c1.1.13 2.09-.65 2.23-1.74c.06-.47-.05-.95-.32-1.35c-2.93-4.31-7.58-12.03-9.22-19.67z");
}

:global(.l757vdbkr) {
  cx: 64.72px;
  cy: 60.54px;
  r: 16.01px;
  fill: var(--svg-color--231f20, #231f20);
}

:global(.ltg6mtw2c) {
  d: path("M64.73 20C19.51 20 5 61.27 5 61.27s12.42 39.85 59.73 39.85c7.34.06 14.64-1.02 21.64-3.21c6 8.49 18.78 12.47 25.3 13.33h.27c1.1-.02 1.99-.93 1.97-2.03a2.04 2.04 0 0 0-.33-1.07c-2.93-4.31-7.58-12-9.22-19.67a60.53 60.53 0 0 0 19.78-27.21S109.95 20 64.73 20");
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

:global(.sv1djk37v) {
  d: path("M104.36 88.48a60.53 60.53 0 0 0 19.78-27.21S109.95 20 64.73 20S5 61.27 5 61.27s12.42 39.85 59.73 39.85c7.34.06 14.64-1.02 21.64-3.21c6 8.49 18.78 12.47 25.3 13.33c1.1.13 2.09-.65 2.23-1.74c.06-.47-.05-.95-.32-1.35c-2.93-4.31-7.58-12.03-9.22-19.67");
}

:global(.xyjtgccot) {
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yxosv3w1o) {
  cx: 64.72px;
  cy: 60.54px;
  r: 28.76px;
  fill: var(--svg-color--3f474c, #3f474c);
}

:global(.zdj3g7b2z) {
  cx: 81.92px;
  cy: 56.34px;
  r: 6.8px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

</style>
