<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bs41d9oln"/><path class="erdfj7vbx"/><path class="o_nzgwnjk"/><path class="vtgsa7bep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:conflict-outline-thin" {...props}></Icon>
<style>
:global(.bs41d9oln) {
  d: path("m3 3 5 5");
}

:global(.erdfj7vbx) {
  d: path("M10.5 7v3.5H7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_nzgwnjk) {
  d: path("m21 21 -5 -5");
}

:global(.vtgsa7bep) {
  d: path("M13.5 17v-3.5H17");
}

</style>
