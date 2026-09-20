<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlnz0-j6y"/><path class="tqmlicc3x"/><path class="ldlcwabvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-spawn-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldlcwabvd) {
  d: path("M13.5 14.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.tqmlicc3x) {
  d: path("M12 11.5v3");
}

:global(.vlnz0-j6y) {
  d: path("M13.9 2.92a4.5 4.5 0 1 1 -3.8 0");
}

</style>
