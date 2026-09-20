<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pvmkd1buc"/><path class="fowtb39ss"/><path class="pilb5jbne"/><path class="olzfpgbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-up-left-duotone-regular" {...props}></Icon>
<style>
:global(.fowtb39ss) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 14V4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olzfpgbos) {
  d: path("M4 14V4h10");
}

:global(.pilb5jbne) {
  d: path("M20 20 4 4");
}

:global(.pvmkd1buc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 20 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
