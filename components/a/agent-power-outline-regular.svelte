<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skbifdbcx"/><path class="hnix93blm"/><path class="gpzsx6dgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-power-outline-regular" {...props}></Icon>
<style>
:global(.gpzsx6dgy) {
  d: path("M16.5 10v5");
}

:global(.hnix93blm) {
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
