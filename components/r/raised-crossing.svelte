<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2wecq9ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:raised-crossing" {...props}></Icon>
<style>
:global(.i2wecq9ws) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 17h20M3 17l4.5-9.5h9L21 17M9.25 10.5V14M12 10.5V14m2.75-3.5V14");
}

</style>
