<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="edi_ohb3j"/><path class="uqdwpgv2x"/><path class="x_5u34bti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ignis" {...props}></Icon>
<style>
:global(.edi_ohb3j) {
  fill: var(--svg-color--f9c011, #f9c011);
  d: path("M14.769 5.534L10.846 3l-3 7.578l1.92 3.499z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.uqdwpgv2x) {
  fill: var(--svg-color--dd6f2c, #dd6f2c);
  d: path("m17.539 9.692l-2.285-3.868l-8.792 15.138h4.408z");
}

:global(.x_5u34bti) {
  fill: var(--svg-color--b6230b, #b6230b);
  d: path("m14.963 15l-3.424 6l5.538-3.286z");
}

</style>
