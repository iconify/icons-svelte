<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="kw1rp87oj"/><path class="skbifdbcx"/><path class="mj0gsdv6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:red-team-agent-duotone-thin" {...props}></Icon>
<style>
:global(.ft030md1w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kw1rp87oj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 10 -4.5 4.5H16L11.5 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mj0gsdv6h) {
  d: path("m18 10 -4.5 4.5H16L11.5 19");
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
