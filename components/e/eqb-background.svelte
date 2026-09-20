<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xwq1e2bkp"/><path clip-rule="evenodd" class="qzb94kbcr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:eqb-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qzb94kbcr) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 18a6 6 0 0 0 1-11.915V9.71a2.5 2.5 0 1 1-2 0V6.085A6 6 0 0 0 12 18m0 2a8 8 0 1 0 0-15.999A8 8 0 0 0 12 20");
}

:global(.xwq1e2bkp) {
  fill: var(--svg-color--4bff00, #4bff00);
  d: path("M24 0H0v24h24z");
}

</style>
