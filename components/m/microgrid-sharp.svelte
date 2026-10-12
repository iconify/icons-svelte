<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z8tcj_b2b"/><circle class="e9-7-8-2z"/><circle class="hnv9gbb9i"/><circle class="io3g52bpb"/><path class="o33surbdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:microgrid-sharp" {...props}></Icon>
<style>
:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.hnv9gbb9i) {
  cx: 4.75px;
  cy: 11px;
  r: 2px;
}

:global(.io3g52bpb) {
  cx: 19.25px;
  cy: 11px;
  r: 2px;
}

:global(.o33surbdg) {
  d: path("M12 6.75v2.5m-5.5 3L8.75 14m8.75-1.75L15.25 14");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z8tcj_b2b) {
  d: path("M8 20.25v-5l.75-.66l2.5-2.18l.75-.66l.75.66l2.5 2.18l.75.66v6H8z");
}

</style>
