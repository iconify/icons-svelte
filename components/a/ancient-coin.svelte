<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ab58msb8v"/><path class="lyvriwg2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ancient-coin" {...props}></Icon>
<style>
:global(.ab58msb8v) {
  d: path("M3.5 10.5a8.5 6 0 1 0 17 0a8.5 6 0 1 0-17 0Z");
}

:global(.lyvriwg2w) {
  d: path("M3.5 10.5v3a8.5 6 0 0 0 17 0v-3m-11-3h5m-4 0v6m3-6v6m-4 0h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
