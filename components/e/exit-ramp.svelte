<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wwg0lprpc"/><path class="fwmidkbpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:exit-ramp" {...props}></Icon>
<style>
:global(.fwmidkbpv) {
  d: path("M14.5 15h7v4h-7Zm3.5 4v2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wwg0lprpc) {
  d: path("M2.5 2.5v19m6 0v-5c0-3.5 2.5-4.5 6-4.5h7m-13-9.5v3c0 2 2.5 3 6 3h7");
}

</style>
