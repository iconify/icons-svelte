<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_fzcqbeu"/><path class="b58isb55w"/><path class="pq9ly31-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:joystick-outline-thin" {...props}></Icon>
<style>
:global(.b_fzcqbeu) {
  d: path("M5 20a7 7 0 0 1 14 0");
}

:global(.b58isb55w) {
  d: path("M12 6v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
