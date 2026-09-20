<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u_iacqbci"/><path class="cw8fumu0q"/><path class="rx3favbug"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hzn-background" {...props}></Icon>
<style>
:global(.cw8fumu0q) {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 12l-2.4-2.4l-1.6 1.6l.8.8l-4.8 4.8l-1.6-1.6l.8-.8l.356.4v-2.356H9.2l.4.356l-2.4 2.4L12 20z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.rx3favbug) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.8 8.8L12 4l-8 8l2.4 2.4L8 12.8l-.8-.8L12 7.2l1.6 1.6l-.8.8l-.356-.4v2.356H14.8l-.4-.356z");
}

:global(.u_iacqbci) {
  fill: var(--svg-color--37f, #37f);
  d: path("M24 0H0v24h24z");
}

</style>
