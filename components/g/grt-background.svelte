<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x2bsx9xyk"/><path clip-rule="evenodd" class="ap9liccan"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:grt-background" {...props}></Icon>
<style>
:global(.ap9liccan) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m-3.333-9c0 1.655 1.346 3 3 3s3-1.345 3-3s-1.347-3-3-3s-3 1.345-3 3m1 0c0-1.103.896-2 2-2c1.103 0 2 .897 2 2s-.897 2-2 2c-1.104 0-2-.897-2-2m4.853 3.853l-2 2a.496.496 0 0 1-.707 0a.5.5 0 0 1 0-.706l2-2a.5.5 0 0 1 .707.706m.047-6.353c0-.33.27-.6.6-.6s.6.27.6.6s-.27.6-.6.6s-.6-.27-.6-.6");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.x2bsx9xyk) {
  fill: var(--svg-color--6f4cff, #6f4cff);
  d: path("M24 0H0v24h24z");
}

</style>
