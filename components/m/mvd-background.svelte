<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bybupwg5g"/><path class="txuc50b_p"/><path class="g2q8w2m2t"/><path class="q_fw2wbfj"/><path class="k1pj96brn"/><path class="nyha7xuam"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mvd-background" {...props}></Icon>
<style>
:global(.bybupwg5g) {
  fill: var(--svg-color--ffaa27, #ffaa27);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g2q8w2m2t) {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 12l4-4V4L4 8z");
}

:global(.k1pj96brn) {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.999 12l-4-4V4l4 4z");
}

:global(.nyha7xuam) {
  fill: var(--svg-color--fff, #fff);
  d: path("m18 10l2 2V8zm-6 2l4-4V4l-4 4.07z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.q_fw2wbfj) {
  fill: var(--svg-color--fff, #fff);
  d: path("m6 10l-2 2V8zm6 2L8 8V4l4 4.07zm8-4l-8 8v4l8-8z");
}

:global(.txuc50b_p) {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 8l8 8v4l-8-8z");
}

</style>
