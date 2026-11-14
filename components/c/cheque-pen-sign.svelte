<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em21xhbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-pen-sign" {...props}></Icon>
<style>
:global(.em21xhbnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 18.5h-10v-13h19v7.6M6 9.5h5.5m-5.5 5h3.5m5.5 6.75l.25-2L19.5 15l1.75 1.75L17 21Z");
}

</style>
