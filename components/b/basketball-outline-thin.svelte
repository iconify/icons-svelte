<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_ssmh9ez"/><path class="h2-2dgnfu"/><path class="c1g3vxf2c"/><path class="o9gvf5b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:basketball-outline-thin" {...props}></Icon>
<style>
:global(.c1g3vxf2c) {
  d: path("M5 6c3 3 3 9 0 12");
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.o9gvf5b1t) {
  d: path("M19 6c-3 3 -3 9 0 12");
}

</style>
