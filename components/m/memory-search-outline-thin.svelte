<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qd2a5rnak"/><path class="sfb1ntbvv"/><path class="zwghjjvbs"/><path class="k5vsxkcxh"/><path class="vfk29flre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-search-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k5vsxkcxh) {
  d: path("M12 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.qd2a5rnak) {
  d: path("M2 6h7");
}

:global(.sfb1ntbvv) {
  d: path("M2 11h7");
}

:global(.vfk29flre) {
  d: path("m19 13 2.5 2.5");
}

:global(.zwghjjvbs) {
  d: path("M2 16h7");
}

</style>
