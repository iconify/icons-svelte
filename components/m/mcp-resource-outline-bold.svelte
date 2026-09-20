<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cacmi2bmi"/><path class="x1_r36phd"/><path class="zm2dyvb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-resource-outline-bold" {...props}></Icon>
<style>
:global(.cacmi2bmi) {
  d: path("M13 3H9L6 6v15h12V8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
