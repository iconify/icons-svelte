<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdlyngb5v"/><path class="f4fg8zbxd"/><path class="pilb5jbne"/><path class="olzfpgbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-up-left-duotone-thin" {...props}></Icon>
<style>
:global(.f4fg8zbxd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14V4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jdlyngb5v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 20 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olzfpgbos) {
  d: path("M4 14V4h10");
}

:global(.pilb5jbne) {
  d: path("M20 20 4 4");
}

</style>
