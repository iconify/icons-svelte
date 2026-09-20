<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cpf_19bsz"/><path class="dea4x_b_q"/><path class="avddsacmh"/><path class="b3x84hb2i"/><path class="m9h6pwgei"/><path class="g2bqhonph"/><path class="g3lrzsbos"/><path class="z_7v15bik"/><path class="cabegubdh"/><path class="ub1mcfbjy"/><path class="xpjur0b_h"/><path class="p0hi_9aen"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-merge-duotone-bold" {...props}></Icon>
<style>
:global(.avddsacmh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b3x84hb2i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cabegubdh) {
  d: path("M14 5h7");
}

:global(.cpf_19bsz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dea4x_b_q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g2bqhonph) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g3lrzsbos) {
  d: path("M3 5h7");
}

:global(.m9h6pwgei) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11.5V14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p0hi_9aen) {
  d: path("M5 17h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ub1mcfbjy) {
  d: path("M14 9h7");
}

:global(.xpjur0b_h) {
  d: path("M12 11.5V14");
}

:global(.z_7v15bik) {
  d: path("M3 9h7");
}

</style>
