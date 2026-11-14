<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ozmqoyh_b"/><path class="ngmfanbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:landing-zone" {...props}></Icon>
<style>
:global(.ngmfanbql) {
  d: path("M7.5 10.5a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0Z");
}

:global(.ozmqoyh_b) {
  d: path("M3 10.5a9 5 0 1 0 18 0a9 5 0 1 0-18 0ZM2.5 19h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
