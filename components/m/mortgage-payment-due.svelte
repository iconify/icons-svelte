<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2fp0s9rv"/><path class="yot-zlb1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-payment-due" {...props}></Icon>
<style>
:global(.p2fp0s9rv) {
  d: path("M11.9 21H3.5V4.5h17v8.8M8 2.5v4m8-4v4m-12.5 3h17M8 13.5h.01m3.99 0h.01M8 17h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yot-zlb1q) {
  d: path("m14.75 17.75l3.25-3l3.25 3v3.5h-6.5Z");
}

</style>
