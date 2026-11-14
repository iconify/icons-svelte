<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqmo89-bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:device-serial-number" {...props}></Icon>
<style>
:global(.qqmo89-bw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5.5h11A3.5 3.5 0 0 1 21 9v6a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 15V9a3.5 3.5 0 0 1 3.5-3.5m0 3.5v6m3-6v6M12 9v6m3-6v6m2.5-6v6");
}

</style>
