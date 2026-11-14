<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e463cgb6g"/><path class="o526cq8lq"/><path class="is8nqnbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:premium-annual" {...props}></Icon>
<style>
:global(.e463cgb6g) {
  d: path("M13 21H3.5V4.5h17v8.4m-17-3.4h17M8 2.5v4m8-4v4");
}

:global(.is8nqnbzt) {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

:global(.o526cq8lq) {
  d: path("M20.75 18.5A2.75 2.75 0 1 1 18 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
