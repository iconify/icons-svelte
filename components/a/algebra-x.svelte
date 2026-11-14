<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjbimzbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:algebra-x" {...props}></Icon>
<style>
:global(.cjbimzbki) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 7l8 10m0-10l-8 10m12-7.5h5m-5 5h5");
}

</style>
