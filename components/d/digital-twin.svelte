<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rbvv3bbxj"/><path class="zjbgyrbix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:digital-twin" {...props}></Icon>
<style>
:global(.rbvv3bbxj) {
  d: path("m10 8l5.25 3v6L10 20l-5.25-3v-6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zjbgyrbix) {
  d: path("M4.75 11L10 14l5.25-3M10 14v6M8.75 6.5l1.75-1m1.75-1l1.75-1l1.75 1m1.75 1l1.75 1v1.75m0 2.5v1.75l-1.75 1");
}

</style>
