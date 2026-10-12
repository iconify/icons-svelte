<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zs6uucbqm"/><circle class="e4h9difwy"/><circle class="jibjxvl9d"/><path class="q6ek88s9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:column-greek-sharp" {...props}></Icon>
<style>
:global(.e4h9difwy) {
  cx: 4.5px;
  cy: 7.25px;
  r: 1.5px;
}

:global(.jibjxvl9d) {
  cx: 19.5px;
  cy: 7.25px;
  r: 1.5px;
}

:global(.q6ek88s9a) {
  d: path("M12 8.75v6.5m-6.5 3h13v3h-13z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zs6uucbqm) {
  d: path("M2.75 2.75h18.5v3H2.75zm6.25 3h6v12.5H9z");
}

</style>
