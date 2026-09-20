<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h-asz9bka"/><path class="c3m9g4nct"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:pdt-background" {...props}></Icon>
<style>
:global(.c3m9g4nct) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 6.896L8.747 12h.005l-.747 1.184H8l-4 6.283V4.533l3.248 5.104l-.752 1.179l-1.21-1.904v6.176L7.247 12l.747-1.184H8l4-6.283l3.248 5.104l-.752 1.179zm4 3.92l4-6.283v14.934l-3.253-5.104l.757-1.184l1.21 1.909V8.912l-1.471 2.31l-.491.778L12 19.467l-3.248-5.104l.752-1.18L12 17.104L15.248 12l.747-1.184z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h-asz9bka) {
  fill: var(--svg-color--8cdc48, #8cdc48);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
