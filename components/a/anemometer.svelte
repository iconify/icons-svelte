<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s84krac4d"/><circle class="f1zl3cc-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:anemometer" {...props}></Icon>
<style>
:global(.f1zl3cc-e) {
  cx: 12px;
  cy: 8px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s84krac4d) {
  d: path("M6.25 8h4m3.5 0h3.75M12 9.75v11.5m-3 0h6M6.25 4.75v6.5a3.25 3.25 0 0 1 0-6.5m14.5 0v6.5a3.25 3.25 0 0 1 0-6.5");
}

</style>
