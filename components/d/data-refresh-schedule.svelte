<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p3z1_pqqw"/><path class="w36328sup"/><path class="f9x9olbpi"/><path class="x53cqrb1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-refresh-schedule" {...props}></Icon>
<style>
:global(.f9x9olbpi) {
  d: path("m18.5 21l-2.5-.5l1-2.5m-8.909 2.383a9.25 9.25 0 0 1 0-16.766");
}

:global(.p3z1_pqqw) {
  d: path("M8 8.5h8V16H8ZM8 11h8m-5.5-3.5v2m3-2v2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w36328sup) {
  d: path("M15.909 3.617a9.25 9.25 0 0 1 0 16.766");
}

:global(.x53cqrb1p) {
  d: path("m5.5 3l2.5.5L7 6");
}

</style>
