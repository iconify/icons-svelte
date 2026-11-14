<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b6z33kl5m"/><path class="pi3jpw3dr"/><path class="vsjz_jngy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:magazine-stack" {...props}></Icon>
<style>
:global(.b6z33kl5m) {
  d: path("M6 7.5h6a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-7A3.5 3.5 0 0 1 6 7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pi3jpw3dr) {
  d: path("M5 4.75h11.25a2 2 0 0 1 2 2V19");
}

:global(.vsjz_jngy) {
  d: path("M7.75 2H19a2 2 0 0 1 2 2v12.25M5.5 11.5h7");
}

</style>
