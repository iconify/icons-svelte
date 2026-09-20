<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d8k3upbuh"/><path class="hf8h13bpe"/><path class="bc5f-jbts"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:azit-background" {...props}></Icon>
<style>
:global(.bc5f-jbts) {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.275 16.364L20 5.697h-6.283l1.105 1.94h1.745L9.818 18.302h9.848l-1.106-1.94z");
}

:global(.d8k3upbuh) {
  fill: var(--svg-color--5550d2, #5550d2);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hf8h13bpe) {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.888 5.925l-.126-.228L4 18.303h2.27l5.502-8.873l5.983 8.873H20z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
