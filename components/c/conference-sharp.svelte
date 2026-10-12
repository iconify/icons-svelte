<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k7dqcnbgn"/><circle class="u_urt4jrw"/><circle class="fggvvekwy"/><circle class="aeekdrycf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:conference-sharp" {...props}></Icon>
<style>
:global(.aeekdrycf) {
  cx: 18.5px;
  cy: 18px;
  r: 2px;
}

:global(.fggvvekwy) {
  cx: 12px;
  cy: 18px;
  r: 2px;
}

:global(.k7dqcnbgn) {
  d: path("M3.75 2.75h16.5v10H3.75zm4 5h8.5");
}

:global(.u_urt4jrw) {
  cx: 5.5px;
  cy: 18px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
