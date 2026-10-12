<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zyb8qn3qj"/><circle class="p87t_gb_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:maze-sharp" {...props}></Icon>
<style>
:global(.p87t_gb_u) {
  cx: 18.75px;
  cy: 18.75px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zyb8qn3qj) {
  d: path("M7.5 3H21v13.5m0 4.5H3V3m4.5 4.5v9H12M12 3v4.5h4.5m0 4.5v4.5M12 12h4.5");
}

</style>
