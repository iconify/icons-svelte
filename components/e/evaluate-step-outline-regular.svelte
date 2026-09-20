<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o5r_prbgx"/><path class="stgd0ptpl"/><path class="olma08bid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:evaluate-step-outline-regular" {...props}></Icon>
<style>
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

:global(.olma08bid) {
  d: path("m13 17 2.5 2.5L20 15");
}

:global(.stgd0ptpl) {
  d: path("m9.5 9.5 3 3");
}

</style>
