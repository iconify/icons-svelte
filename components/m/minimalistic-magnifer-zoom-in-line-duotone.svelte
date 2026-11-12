<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGwJRune3D"><g class="k2u665ban"><circle class="b4dyhhbeb"/><path class="vi5lk__sd"/></g></mask></defs><path mask="url(#SVGwJRune3D)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifer-zoom-in-line-duotone" {...props}></Icon>
<style>
:global(.b4dyhhbeb) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  stroke: var(--svg-color--gray, gray);
}

:global(.k2u665ban) {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vi5lk__sd) {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M9 11.5h2.5m0 0H14m-2.5 0V14m0-2.5V9M20 20l2 2");
}

:global(.w49j0rbvv) {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

</style>
