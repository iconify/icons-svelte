<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aut-6nhkz"/><path class="ac5nw33zc"/><path class="pt-3kkb2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pipette-outline-thin" {...props}></Icon>
<style>
:global(.ac5nw33zc) {
  d: path("M9 6a3 3 0 0 1 6 0");
}

:global(.aut-6nhkz) {
  d: path("M9 6h6v9l-3 3 -3 -3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pt-3kkb2k) {
  d: path("M9 11h6");
}

</style>
