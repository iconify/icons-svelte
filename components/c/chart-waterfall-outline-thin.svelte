<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nt8ufs66i"/><path class="ig8k5lhpw"/><path class="hlt9oudyd"/><path class="goqqd75_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-waterfall-outline-thin" {...props}></Icon>
<style>
:global(.goqqd75_r) {
  d: path("M20 4v5");
}

:global(.hlt9oudyd) {
  d: path("M15 9v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ig8k5lhpw) {
  d: path("M10 11v5");
}

:global(.nt8ufs66i) {
  d: path("M5 6v5");
}

</style>
