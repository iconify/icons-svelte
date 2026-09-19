<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGc7J4mcYb" class="g04sjyg1g"/></defs><path class="dlfb-5bfp"/><use href="#SVGc7J4mcYb" class="c-zrgpb5l"/><path class="ratff_bjj"/><use href="#SVGc7J4mcYb" class="c-zrgpb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-eye-in-speech-bubble" {...props}></Icon>
<style>
:global(.c-zrgpb5l) {
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dlfb-5bfp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.154c4.678 7.77 13.325 12.345 19.243 13.994c2.953.824 10.495 6.347 10.495 6.347s-1.882-5.53-2.196-7.445c-1.195-7.271 8.502-8.136 9.458-13.32c-5.553-12.905-25.08-24.39-37 .425");
}

:global(.g04sjyg1g) {
  fill: none;
  stroke: currentColor;
  d: path("M18.864 20.544a5.065 5.065 0 1 0 10.13 0a5.065 5.065 0 0 0-10.13 0");
}

:global(.ratff_bjj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.671 20.544a9.257 9.257 0 0 0 9.252 9.263a9.257 9.257 0 0 0 9.263-9.251v-.012a9.257 9.257 0 0 0-9.253-9.26a9.257 9.257 0 0 0-9.262 9.253z");
}

</style>
