<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="jkiommvhg"/><circle class="ngu0943hg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:looper-sharp" {...props}></Icon>
<style>
:global(.bh4biibbp) {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

:global(.jkiommvhg) {
  d: path("M15.5 9.5a3.5 3.5 0 1 1-1.03-2.47m0-2v2h-2");
}

:global(.ngu0943hg) {
  cx: 12px;
  cy: 17.25px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
