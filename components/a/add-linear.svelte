<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hw_sn9wmj"/><path class="etg41e6bw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:add-linear" {...props}></Icon>
<style>
:global(.etg41e6bw) {
  d: path("M12.0204 4L12.0205 20.0003");
}

:global(.hw_sn9wmj) {
  d: path("M4 12L20 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
