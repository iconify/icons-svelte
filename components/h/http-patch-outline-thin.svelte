<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="gwhfoytcg"/><path class="w4_ysudzy"/><path class="v_f8cdb5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:http-patch-outline-thin" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.gwhfoytcg) {
  d: path("M12 7.5v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.v_f8cdb5o) {
  d: path("M10 14.5h4");
}

:global(.w4_ysudzy) {
  d: path("M10 9.5h4");
}

</style>
