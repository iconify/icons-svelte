<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ohaw43bvl"/><path class="qp0zyybio"/><path class="ozpoglbbx"/><path class="wv9ug2bbl"/><path class="o8od38cnm"/><path class="juq6zh-od"/><path class="qq2awqbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:currency-exchange-outline-regular" {...props}></Icon>
<style>
:global(.juq6zh-od) {
  d: path("M6.5 15.5 4 18l2.5 2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.ohaw43bvl) {
  d: path("M2.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.ozpoglbbx) {
  d: path("M12.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.qp0zyybio) {
  d: path("M7 5.5v5");
}

:global(.qq2awqbbs) {
  d: path("M17.5 15.5 20 18l-2.5 2.5");
}

:global(.wv9ug2bbl) {
  d: path("M17 5.5v5");
}

</style>
