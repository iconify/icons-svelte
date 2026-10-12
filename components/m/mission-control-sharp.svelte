<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e-j0bqyrj"/><path class="q_--6vbma"/><path class="d6fbly8nu"/><path class="r1ig1xl0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mission-control-sharp" {...props}></Icon>
<style>
:global(.d6fbly8nu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 7.25h.01");
}

:global(.e-j0bqyrj) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3h18.5v11.25H2.75z");
}

:global(.q_--6vbma) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11c2-3.25 5.5-4.75 10-4.25");
}

:global(.r1ig1xl0h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15v2m-6.75.75h14.5l.39.92l.72 1.66l.39.92H2.75l.39-.92l.72-1.66l.39-.92z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
