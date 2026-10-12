<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r3e42nbki"/><path class="mujg5gpoa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ai-researcher-sharp" {...props}></Icon>
<style>
:global(.mujg5gpoa) {
  d: path("M12 12.5q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25Z");
}

:global(.r3e42nbki) {
  d: path("M10 3.75h4v4.5l5.75 10.25l1.338 2.673l-2.988.077H5.9l-2.988-.077L4.25 18.5L10 8.25Zm-1.75 0h7.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
