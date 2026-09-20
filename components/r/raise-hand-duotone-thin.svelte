<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mgib8v4wh"/><path class="r15ruzbdn"/><path class="n5c3em2az"/><path class="xar3kncqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:raise-hand-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mgib8v4wh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v4a2 2 0 0 1 4 0v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n5c3em2az) {
  d: path("M7 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v4a2 2 0 0 1 4 0v4");
}

:global(.r15ruzbdn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xar3kncqc) {
  d: path("M15 9V4");
}

</style>
