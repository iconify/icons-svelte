<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jvmeqobay"/><path class="uw7m5l0-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calculator-clear" {...props}></Icon>
<style>
:global(.jvmeqobay) {
  d: path("M12.1 21H3.5V2.5h14v11.1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uw7m5l0-j) {
  d: path("M6.5 5.5h8V9h-8Zm1 8h.01m3.49 0h.01m-3.51 4h.01m7.99-2l5 5m0-5l-5 5");
}

</style>
