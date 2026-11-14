<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ae_vmwbwm"/><path class="ykh9yh77u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:garden-measuring-tape" {...props}></Icon>
<style>
:global(.ae_vmwbwm) {
  d: path("M5.5 4.5H14a3 3 0 0 1 3 3V19H5.5a3 3 0 0 1-3-3V7.5a3 3 0 0 1 3-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ykh9yh77u) {
  d: path("M6.75 11.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM17 15.5h4.5V19H17");
}

</style>
