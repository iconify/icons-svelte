<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_uvnuivb"/><path class="uhty14kih"/><path class="f50v0cimy"/><path class="v5d935don"/><path class="ef5tcc6_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fence-outline-thin" {...props}></Icon>
<style>
:global(.ef5tcc6_c) {
  d: path("M4 16h14");
}

:global(.f50v0cimy) {
  d: path("M18 7v14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_uvnuivb) {
  d: path("M4 7v14");
}

:global(.uhty14kih) {
  d: path("M11 7v14");
}

:global(.v5d935don) {
  d: path("M4 11h14");
}

</style>
