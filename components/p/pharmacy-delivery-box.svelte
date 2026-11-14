<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fncur87gl"/><path class="vu230mbui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pharmacy-delivery-box" {...props}></Icon>
<style>
:global(.fncur87gl) {
  d: path("M11.6 19H2.5V3h17v8.7M2.5 8h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vu230mbui) {
  d: path("M9.25 3v8.5h4.5V3M18 14.5v7m-3-3l3 3l3-3");
}

</style>
