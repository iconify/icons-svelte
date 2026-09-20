<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7dgfu7wx"/><path class="d1zyr9bfc"/><path class="lvnmieb7r"/><path class="y07a50u1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cable-car-outline-thin" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lvnmieb7r) {
  d: path("M5 10a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.y07a50u1t) {
  d: path("M5 13h14");
}

</style>
