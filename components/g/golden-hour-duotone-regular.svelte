<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xvqk2nbnq"/><path class="mbt4yzbhr"/><path class="kp2-aab3h"/><path class="b7f-z_e-v"/><path class="bm-d2pd6d"/><path class="j6errpbqe"/><path class="grgwcd1mp"/><path class="z9ittvbis"/><path class="h4br4z40f"/><path class="e0fatccfd"/><path class="sdu5ckfnu"/><path class="sxnekjbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:golden-hour-duotone-regular" {...props}></Icon>
<style>
:global(.b7f-z_e-v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bm-d2pd6d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 6 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e0fatccfd) {
  d: path("M18 12h4");
}

:global(.grgwcd1mp) {
  d: path("M7.5 17a4.5 4.5 0 0 1 9 0");
}

:global(.h4br4z40f) {
  d: path("M2 12h4");
}

:global(.j6errpbqe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 6 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kp2-aab3h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sdu5ckfnu) {
  d: path("m5 6 3 3");
}

:global(.sxnekjbzh) {
  d: path("m19 6 -3 3");
}

:global(.xvqk2nbnq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 17a4.5 4.5 0 0 1 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
