<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="li19mgbhm"/><path class="a-ogebbgz"/><path class="fl5-97bom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:api-quota-outline-bold" {...props}></Icon>
<style>
:global(.a-ogebbgz) {
  d: path("M12 7v9");
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.fl5-97bom) {
  d: path("M15 12v4");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.li19mgbhm) {
  d: path("M9 10v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
