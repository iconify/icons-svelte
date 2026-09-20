<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g8lhti-nz"/><path class="m0rn-ccfu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:diko-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g8lhti-nz) {
  fill: var(--svg-color--212937, #212937);
  d: path("M24 0H0v24h24z");
}

:global(.m0rn-ccfu) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.075 6.403a.71.71 0 0 1 .65-.405h3.06c.25 0 .486.13.61.34l6.502 10.608c.136.22.136.485.01.7a.71.71 0 0 1-.62.35h-3.2a.68.68 0 0 1-.506-.2a8.4 8.4 0 0 0-4.31-2.15c-1.811-.286-3.952.104-6.052 2.15a.726.726 0 0 1-.916.08a.69.69 0 0 1-.24-.86L9.07 6.398zM11 7.498l5.502 9.003h1.525l-5.652-9.003zm2.87 7.497L9.8 8.198l-3.251 6.887a7.87 7.87 0 0 1 4.951-.815c.85.135 1.65.4 2.37.72z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
