<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xikk_ob4f"/><path class="y04hpebpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bullet-chart-sharp" {...props}></Icon>
<style>
:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xikk_ob4f) {
  d: path("M2.75 8h18.5v8H2.75z");
}

:global(.y04hpebpa) {
  d: path("M5 10.5h9.5v3H5zM17.5 5v14");
}

</style>
