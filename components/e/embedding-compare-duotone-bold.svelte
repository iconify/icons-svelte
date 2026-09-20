<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xnapskfbz"/><path class="l1xqqc5ux"/><path class="mqtvn8eza"/><path class="fyjnwtd1v"/><path class="p0mfrtbaw"/><path class="vs9x-_bah"/><path class="hclo6jb2r"/><path class="ubmhydvvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embedding-compare-duotone-bold" {...props}></Icon>
<style>
:global(.fyjnwtd1v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 19.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.l1xqqc5ux) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.5 5 22 7.5l-4 4 -4 -4L16.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mqtvn8eza) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 16h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p0mfrtbaw) {
  d: path("M7.5 5 10 7.5l-4 4 -4 -4L4.5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ubmhydvvx) {
  d: path("M8 19.5h8");
}

:global(.vs9x-_bah) {
  d: path("M19.5 5 22 7.5l-4 4 -4 -4L16.5 5");
}

:global(.xnapskfbz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 5 10 7.5l-4 4 -4 -4L4.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
