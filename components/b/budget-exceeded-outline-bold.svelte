<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="u0f6w1z_e"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:budget-exceeded-outline-bold" {...props}></Icon>
<style>
:global(.csyuhrrop) {
  d: path("M5 14V3h14v11");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nreq_9ofo) {
  d: path("M2 11v10h20V11L12 21Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u0f6w1z_e) {
  d: path("M12 6v3");
}

</style>
