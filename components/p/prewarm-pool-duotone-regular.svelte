<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vssdnxb_k"/><path class="rq8i8945v"/><path class="sg0x-3a_x"/><path class="quu8uycwi"/><path class="j4ecinbzh"/><path class="er6s1rc2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prewarm-pool-duotone-regular" {...props}></Icon>
<style>
:global(.er6s1rc2j) {
  d: path("m15 11 2 -2 -2 -2");
}

:global(.j4ecinbzh) {
  d: path("m9 11 2 -2 -2 -2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.quu8uycwi) {
  d: path("M3 14v5h18v-5");
}

:global(.rq8i8945v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 11 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sg0x-3a_x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 11 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vssdnxb_k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14v5h18v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
