<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="rn7eq5-kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:phrasebook-sharp" {...props}></Icon>
<style>
:global(.bh4biibbp) {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

:global(.rn7eq5-kt) {
  d: path("M9 8h7v5h-4.5l-2 1.75V13H8V8zm-4.25 9.75h14.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
