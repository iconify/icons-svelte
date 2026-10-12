<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np29o6bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fitness-band-sharp" {...props}></Icon>
<style>
:global(.np29o6bbt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.25h7v11.5h-7zm1.25 0l-.5-3.5m5 3.5l.5-3.5m-5 15l-.5 3.5m5-3.5l.5 3.5M12 9.75v4.5");
}

</style>
