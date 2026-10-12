<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e27_xcgye"/><circle class="m1is5jemp"/><path class="z0qge-b2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:on-air-sharp" {...props}></Icon>
<style>
:global(.e27_xcgye) {
  d: path("M2.75 7.5h18.5v9H2.75z");
}

:global(.m1is5jemp) {
  cx: 7.75px;
  cy: 12px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0qge-b2w) {
  d: path("M12.25 12h5.5");
}

</style>
