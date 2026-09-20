<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jlfjgzbqx"/><path class="dl7inkt3h"/><path class="ae0h5kb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:format-check-outline-bold" {...props}></Icon>
<style>
:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.dl7inkt3h) {
  d: path("M10.5 12H15");
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
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
