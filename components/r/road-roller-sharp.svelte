<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="scwzwtbmo"/><path class="a0l7g9b7f"/><path class="c_e68kbml"/><circle class="zxq2seyyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:road-roller-sharp" {...props}></Icon>
<style>
:global(.a0l7g9b7f) {
  d: path("M2.85 12.8a6.25 6.25 0 0 1 9.3 0");
}

:global(.c_e68kbml) {
  d: path("M12 9h9.25v4.75H12zm1.5 0V4.75H20V9m-7.5-4.25H21");
}

:global(.scwzwtbmo) {
  cx: 7.5px;
  cy: 17px;
  r: 3.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxq2seyyq) {
  cx: 17px;
  cy: 18.75px;
  r: 2.5px;
}

</style>
