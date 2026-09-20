<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yuaxbqe-i"/><path class="b045_jvuf"/><path class="goxee6bnt"/><path class="ps3-67b_v"/><path class="wlia6bb5b"/><path class="adiugjbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:encoder-duotone-regular" {...props}></Icon>
<style>
:global(.adiugjbhs) {
  d: path("m15 9 3 3 -3 3");
}

:global(.b045_jvuf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.goxee6bnt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ps3-67b_v) {
  d: path("m4 3 6 6v6l-6 6");
}

:global(.wlia6bb5b) {
  d: path("M11 12h7");
}

:global(.yuaxbqe-i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 3 6 6v6l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
