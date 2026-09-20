<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cacmi2bmi"/><path class="pty_wsbvs"/><path class="pgcrrz33a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-logging-outline-thin" {...props}></Icon>
<style>
:global(.cacmi2bmi) {
  d: path("M13 3H9L6 6v15h12V8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pgcrrz33a) {
  d: path("m10 13.5 2 2 2 -2");
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

</style>
