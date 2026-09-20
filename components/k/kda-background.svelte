<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tl7b3xbpt"/><path class="m9ctkb9fh"/><path class="y0khasbsd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:kda-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.m9ctkb9fh) {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.428 20h-4.952l-5.08-7.238l2.032-4.19zM4.571 4h4v16h-4z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.tl7b3xbpt) {
  fill: var(--svg-color--6a0097, #6a0097);
  d: path("M24 0H0v24h24z");
}

:global(.y0khasbsd) {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.54 4h-4.572L8.571 9.5v4.998z");
}

</style>
