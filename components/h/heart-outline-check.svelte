<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="myc35iv5s"/><path class="jo34ko0tj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heart-outline-check" {...props}></Icon>
<style>
:global(.jo34ko0tj) {
  d: path("m8.5 12l2.5 2.5l4.5-4.5");
}

:global(.myc35iv5s) {
  d: path("M12 20.5c-5-3.5-9.5-7-9.5-11.75A5 5 0 0 1 12 6.5a5 5 0 0 1 9.5 2.25C21.5 13.5 17 17 12 20.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
