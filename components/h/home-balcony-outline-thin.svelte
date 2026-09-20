<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tj_906bjf"/><path class="l8dn9jbyp"/><path class="w60p31c9m"/><path class="e2nq-yvbg"/><path class="e-3fufbxq"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-balcony-outline-thin" {...props}></Icon>
<style>
:global(.e-3fufbxq) {
  d: path("M19 15v6");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.tj_906bjf) {
  d: path("M4 3v9h16V3");
}

:global(.w60p31c9m) {
  d: path("M5 15v6");
}

</style>
