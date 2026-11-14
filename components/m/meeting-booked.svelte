<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d925dqbjv"/><path class="uauzs9bqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:meeting-booked" {...props}></Icon>
<style>
:global(.d925dqbjv) {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4");
}

:global(.uauzs9bqj) {
  d: path("m7.5 13.5l3.25 3.25L16.5 11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
