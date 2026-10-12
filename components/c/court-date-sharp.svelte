<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rm8a8dbar"/><path class="ehlhcub7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:court-date-sharp" {...props}></Icon>
<style>
:global(.ehlhcub7x) {
  d: path("m7.93 13.49l3.64-2.23L12 11l.43.26l3.64 2.23l.43.26h-9zM9.25 15v2M12 15v2m2.75-2v2M7.5 18.25h9");
}

:global(.rm8a8dbar) {
  d: path("M2.75 4.25h18.5v17H2.75zM8 2.75v3m8-3v3M2.75 9h18.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
