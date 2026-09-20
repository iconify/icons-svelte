<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s0nbkdb4m"/><path class="r5ukg2brx"/><path class="n5c3em2az"/><path class="xar3kncqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:raise-hand-duotone-regular" {...props}></Icon>
<style>
:global(.n5c3em2az) {
  d: path("M7 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v4a2 2 0 0 1 4 0v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r5ukg2brx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0nbkdb4m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v4a2 2 0 0 1 4 0v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xar3kncqc) {
  d: path("M15 9V4");
}

</style>
