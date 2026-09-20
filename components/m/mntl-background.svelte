<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="im4wmbbyb"/><path class="st_jms73l"/><path class="mvd9o9nwc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mntl-background" {...props}></Icon>
<style>
:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.im4wmbbyb) {
  fill: var(--svg-color--0d0a03, #0d0a03);
  d: path("M15.111 16.89a1.334 1.334 0 1 0 0-2.667a1.334 1.334 0 0 0 0 2.667");
}

:global(.mvd9o9nwc) {
  fill: var(--svg-color--0d0a03, #0d0a03);
  d: path("M5.6 6.667h5.333a1.6 1.6 0 0 1 1.303 2.529l-5.334 7.467A1.6 1.6 0 0 1 4 15.738V8.267a1.6 1.6 0 0 1 1.6-1.6m.844 4a1.11 1.11 0 1 0 0-2.222a1.11 1.11 0 0 0 0 2.222");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.st_jms73l) {
  fill: var(--svg-color--fcbe33, #fcbe33);
  d: path("M20 8.267v7.467a1.613 1.613 0 0 1-1.449 1.59c-.987.094-1.653-.653-1.662-1.59v-1.218c0-.338-.196-.667-.4-.934a1.6 1.6 0 0 0-2.578.018l-.831 1.165l-1.338 1.88a1.6 1.6 0 0 1-2.587-1.871l5.325-7.467a1.6 1.6 0 0 1 1.262-.64h2.662A1.6 1.6 0 0 1 20 8.267");
}

</style>
