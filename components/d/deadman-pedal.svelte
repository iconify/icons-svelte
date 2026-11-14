<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6v-64yfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deadman-pedal" {...props}></Icon>
<style>
:global(.l6v-64yfo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.67 10.492l10.625-2.847l1.035 3.863l-10.625 2.847ZM8.5 20.5L16 13M2.5 20.5h19M4.5 3v8.5M2.25 9.25L4.5 11.5l2.25-2.25");
}

</style>
