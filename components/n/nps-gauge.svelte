<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb4_jac-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nps-gauge" {...props}></Icon>
<style>
:global(.cb4_jac-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17a9.5 9.5 0 0 1 19 0M3.75 12.25L6 13.5m6-6V10m8.25 2.25L18 13.5M12 17l2.75-4.75M12 17h.01");
}

</style>
