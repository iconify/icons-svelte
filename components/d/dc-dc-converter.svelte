<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhq2nubgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dc-dc-converter" {...props}></Icon>
<style>
:global(.vhq2nubgc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6h5A3.5 3.5 0 0 1 18 9.5v5a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 14.5v-5A3.5 3.5 0 0 1 9.5 6M2 12h4m12 0h4M9 10.5h6m-6 3h1.5m2.75 0H15");
}

</style>
