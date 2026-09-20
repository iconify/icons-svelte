<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hiue4sblj"/><path class="u5kuez3us"/><path class="g31q_jb0h"/><path class="pftwmngyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-prompt-duotone-bold" {...props}></Icon>
<style>
:global(.g31q_jb0h) {
  d: path("M9 10v4");
}

:global(.hiue4sblj) {
  fill: currentColor;
  d: path("M15.5 6H18a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3v-4l5 -5h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pftwmngyp) {
  d: path("M12 12h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u5kuez3us) {
  d: path("M15.5 6H18a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3v-4l5 -5h2.5");
}

</style>
