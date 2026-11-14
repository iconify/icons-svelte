<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdst_7bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:octagon" {...props}></Icon>
<style>
:global(.tdst_7bmh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 3.761L20.239 7.5a2.63 2.63 0 0 1 .769 1.856v5.288a2.63 2.63 0 0 1-.769 1.856L16.5 20.239a2.63 2.63 0 0 1-1.856.769H9.356a2.63 2.63 0 0 1-1.856-.769L3.761 16.5a2.63 2.63 0 0 1-.769-1.856V9.356A2.63 2.63 0 0 1 3.761 7.5L7.5 3.761a2.63 2.63 0 0 1 1.856-.769h5.288a2.63 2.63 0 0 1 1.856.769");
}

</style>
