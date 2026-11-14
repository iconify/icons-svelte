<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gwdha7bjd"/><path class="krr_-1bmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battlecard" {...props}></Icon>
<style>
:global(.gwdha7bjd) {
  d: path("m9 18.5l-3.75.75L2 4.75l9.75-2.25l.75 3");
}

:global(.krr_-1bmc) {
  d: path("M9 5.5h11.5V21H9Zm3.25 4.5h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
