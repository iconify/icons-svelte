<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="saqbxe1ne"/><path class="blpqvobsg"/><path class="gh_b-0fuf"/><path class="lrkxnckco"/><path class="aoorvnbzq"/><path class="e-eh9i0mi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-review-duotone-thin" {...props}></Icon>
<style>
:global(.aoorvnbzq) {
  d: path("m14 7 4 4 -4 4");
}

:global(.blpqvobsg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 7 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e-eh9i0mi) {
  d: path("m9 19 2 2 4 -4");
}

:global(.gh_b-0fuf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 19 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lrkxnckco) {
  d: path("m8 7 -4 4 4 4");
}

:global(.saqbxe1ne) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 7 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
