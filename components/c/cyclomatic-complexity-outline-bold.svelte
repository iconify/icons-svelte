<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="b_x7v_t0t"/><path class="bx3fv3b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cyclomatic-complexity-outline-bold" {...props}></Icon>
<style>
:global(.b_x7v_t0t) {
  d: path("m12 7 3 3 -3 3 -3 -3Z");
}

:global(.bx3fv3b8c) {
  d: path("M12 13v4");
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
