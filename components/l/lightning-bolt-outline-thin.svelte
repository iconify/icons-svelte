<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mbgtdkbsk"/><path class="flblq5ico"/><path class="zsil77j-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lightning-bolt-outline-thin" {...props}></Icon>
<style>
:global(.flblq5ico) {
  d: path("m13 14 6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mbgtdkbsk) {
  d: path("m16 2 -8 8h5l-8 8");
}

:global(.zsil77j-s) {
  d: path("m19 14 -6 6");
}

</style>
