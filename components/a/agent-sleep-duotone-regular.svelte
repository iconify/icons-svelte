<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="r_wa75tbp"/><path class="skbifdbcx"/><path class="d0vyaobih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-sleep-duotone-regular" {...props}></Icon>
<style>
:global(.d0vyaobih) {
  d: path("M13 12h8l-8 8h8");
}

:global(.kosxb-loy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r_wa75tbp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h8l-8 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
