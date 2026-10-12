<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wxkih3bpl"/><path class="bqzpaxbek"/><circle class="cey46ju5m"/><path class="denqkxbyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quarantine-sign" {...props}></Icon>
<style>
:global(.bqzpaxbek) {
  d: path("M7.5 14.75v6.5m9-6.5v6.5");
}

:global(.cey46ju5m) {
  cx: 12px;
  cy: 9px;
  r: 2.25px;
}

:global(.denqkxbyj) {
  d: path("M12 4.75v1m0 6.5v1M7.75 9h1m6.5 0h1M9 6l.7.7M15 6l-.7.7M9 12l.7-.7m5.3.7l-.7-.7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wxkih3bpl) {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

</style>
