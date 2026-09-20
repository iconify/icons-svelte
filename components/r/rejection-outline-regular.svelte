<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o5r_prbgx"/><path class="bmsk64_re"/><path class="fmv013bbw"/><path class="bxyszcb7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rejection-outline-regular" {...props}></Icon>
<style>
:global(.bmsk64_re) {
  d: path("M9.5 9.5 12 12");
}

:global(.bxyszcb7e) {
  d: path("m20 15 -5 5");
}

:global(.fmv013bbw) {
  d: path("m15 15 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o5r_prbgx) {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
