<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j3wu6pb4g"/><path class="y0jjn0phn"/><path class="yazo7scbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:acorn-outline-bold" {...props}></Icon>
<style>
:global(.j3wu6pb4g) {
  d: path("M6 9a6 6 0 0 0 12 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y0jjn0phn) {
  d: path("M7 9a5 5 0 0 0 5 10 5 5 0 0 0 5 -10");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
