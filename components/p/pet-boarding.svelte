<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c4lyeub3g"/><path class="x6bad17vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pet-boarding" {...props}></Icon>
<style>
:global(.c4lyeub3g) {
  d: path("M12 18.5H2.5V5h17v6.8M8.5 5V2.75h5V5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x6bad17vm) {
  d: path("M5.5 18.5v-5a3 3 0 0 1 6 0v5m6.5-3.75a3.5 3.5 0 1 0 3.75 3.75A3 3 0 0 1 18 14.75Z");
}

</style>
