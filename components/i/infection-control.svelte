<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="bnjnom5xi"/><path class="eqcbvrb9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:infection-control" {...props}></Icon>
<style>
:global(.bnjnom5xi) {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.eqcbvrb9h) {
  d: path("m13.25 9l.75-.5l-.5-.75m1.5 3l1 .25l.25-1M15 13.25l.5.75l1-.5M13.25 15v1l.75.25M10.75 15l-.75.5l.5 1M9 13.25h-.75L8 14m1-3.25L8.5 10l-.75.5m3-1.5l.25-.75L10 8M5.25 5.25l13.5 13.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
