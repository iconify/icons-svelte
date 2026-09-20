<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l1o-n1ybz"/><path class="kglkvw7qp"/><path class="lywbwbcjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ltx" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kglkvw7qp) {
  fill: var(--svg-color--000, #000);
  d: path("M18.75 3v4.5L5.25 20.98V16.5z");
}

:global(.l1o-n1ybz) {
  fill: var(--svg-color--fc0, #fc0);
  d: path("M5.25 3L12 9.75l-2.13 2.365L5.25 7.5z");
}

:global(.lywbwbcjy) {
  fill: var(--svg-color--fc0, #fc0);
  d: path("M18.75 16.5V21L12 14.25v-4.5z");
}

</style>
