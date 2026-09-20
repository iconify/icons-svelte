<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n-o3_dq-g"/><path class="wchqdzgig"/><path class="xt2a22bam"/><path class="itl0kjbca"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hxd-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.itl0kjbca) {
  fill: var(--svg-color--000, #000);
  d: path("M18.5 15h-4v5l4-2.25z");
}

:global(.n-o3_dq-g) {
  fill: var(--svg-color--f8c007, #f8c007);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.wchqdzgig) {
  fill: var(--svg-color--000, #000);
  d: path("M5.5 6.25V9h4V4z");
}

:global(.xt2a22bam) {
  fill: var(--svg-color--000, #000);
  d: path("M14.5 10h-9v1.5h13V6.25L14.5 4zm4 4v-1.5h-13V18l4 2v-6z");
}

</style>
