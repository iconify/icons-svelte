<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yg02iti_h"/><path class="kk_9y6czk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:company-x" {...props}></Icon>
<style>
:global(.kk_9y6czk) {
  d: path("M9.5 21.5v-4h3v2.1m0-13.1h.01M12.5 11h.01m2.99 4.5l5 5m0-5l-5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yg02iti_h) {
  d: path("M12.6 21.5H3V9h5V2.5h9v10.6");
}

</style>
