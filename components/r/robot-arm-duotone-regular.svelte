<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e79pod60b"/><path class="bphmvlb8r"/><path class="i-ztrxcqw"/><path class="gbszb4bja"/><path class="o46_3ibvz"/><path class="gzh4n16ws"/><path class="b6ubinbne"/><path class="ti0atfbnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:robot-arm-duotone-regular" {...props}></Icon>
<style>
:global(.b6ubinbne) {
  d: path("m6 12 6 -6h8v3.5");
}

:global(.bphmvlb8r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e79pod60b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gbszb4bja) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 6v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gzh4n16ws) {
  d: path("M6 12v8");
}

:global(.i-ztrxcqw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 12 6 -6h8v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o46_3ibvz) {
  d: path("M3 20h6");
}

:global(.ti0atfbnf) {
  d: path("M17 6v3.5");
}

</style>
