<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="iy_rpdbrd"/><path class="tw4p0cbva"/><path class="d89cd-vmo"/><path class="szt0loaqj"/><path class="inq_2fh0z"/><path class="fjydvsd3v"/><path class="yxmtpwgfv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:nexa-background" {...props}></Icon>
<style>
:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.d89cd-vmo) {
  fill: var(--svg-color--ffe144, #ffe144);
  d: path("M20 6.587H4l8 8.47z");
}

:global(.fjydvsd3v) {
  fill: var(--svg-color--b6761c, #b6761c);
  d: path("M12 7.803L8.233 4.236L12 10.354z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.inq_2fh0z) {
  fill: var(--svg-color--fffd9d, #fffd9d);
  d: path("m12 7.803l3.765-3.567L12 10.354z");
}

:global(.iy_rpdbrd) {
  fill: var(--svg-color--fffd9d, #fffd9d);
  d: path("m12 15.058l8-8.47l-8 13.176z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.szt0loaqj) {
  fill: var(--svg-color--b6761c, #b6761c);
  d: path("M15.293 8.47H8.705L12 11.764z");
}

:global(.tw4p0cbva) {
  fill: var(--svg-color--b6761c, #b6761c);
  d: path("m12 15.058l-8-8.47l8 13.176z");
}

:global(.yxmtpwgfv) {
  fill: var(--svg-color--ffe144, #ffe144);
  d: path("M15.764 4.236h-7.53L12 7.803z");
}

</style>
