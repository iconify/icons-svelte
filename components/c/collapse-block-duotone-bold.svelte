<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="svfnzifuy"/><path class="e-s5j7bdg"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="is4rzhsst"/><path class="tc-ybhuxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collapse-block-duotone-bold" {...props}></Icon>
<style>
:global(.c1kziyotx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.e-s5j7bdg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 17 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hieqhxiaw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.is4rzhsst) {
  d: path("m10 7 2 2 2 -2");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.svfnzifuy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 7 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tc-ybhuxl) {
  d: path("m10 17 2 -2 2 2");
}

</style>
