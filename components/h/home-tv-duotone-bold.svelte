<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r39poztgk"/><path class="mjfvqdb6k"/><path class="pa9quik2g"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-tv-duotone-bold" {...props}></Icon>
<style>
:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.mjfvqdb6k) {
  d: path("M3 5v11h18V5Z");
}

:global(.pa9quik2g) {
  d: path("M12 16v3");
}

:global(.r39poztgk) {
  fill: currentColor;
  d: path("M3 5v11h18V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
