<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fb74ufi-y"/><path class="gdn1l_odj"/><path class="kyeltuukk"/><path class="vlnz0-j6y"/><path class="tqmlicc3x"/><path class="ldlcwabvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-spawn-duotone-thin" {...props}></Icon>
<style>
:global(.fb74ufi-y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.9 2.92a4.5 4.5 0 1 1 -3.8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gdn1l_odj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kyeltuukk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 14.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
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
