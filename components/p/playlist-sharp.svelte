<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vhot-xehv"/><circle class="k04vwvbgs"/><path class="o2evx_fhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:playlist-sharp" {...props}></Icon>
<style>
:global(.k04vwvbgs) {
  cx: 15.25px;
  cy: 17.75px;
  r: 2.5px;
}

:global(.o2evx_fhq) {
  d: path("M17.75 17.75v-8l.717 1.863L21.25 12");
}

:global(.vhot-xehv) {
  d: path("M3.75 5.75h12.5m-12.5 5h12.5m-12.5 5h6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
