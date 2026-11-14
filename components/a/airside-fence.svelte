<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpns6zn-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:airside-fence" {...props}></Icon>
<style>
:global(.wpns6zn-w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V6l1.5-2L6 6v15m4.5 0V6L12 4l1.5 2v15m4.5 0V6l1.5-2L21 6v15M6 9.5h4.5m-4.5 6h4.5");
}

</style>
