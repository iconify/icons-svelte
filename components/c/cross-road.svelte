<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_6hdcu0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cross-road" {...props}></Icon>
<style>
:global(.m_6hdcu0c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5V9H2.5M15 2.5V9h6.5m-19 6H9v6.5M21.5 15H15v6.5m-3-19V6m0 12v3.5M2.5 12H6m12 0h3.5");
}

</style>
