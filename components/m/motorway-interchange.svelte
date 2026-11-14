<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf3jgmbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:motorway-interchange" {...props}></Icon>
<style>
:global(.lf3jgmbjk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M2.5 12h6.75m5.5 0h6.75M12 8.5a3.5 3.5 0 1 1 3.5 3.5m-7 0A3.5 3.5 0 1 1 12 8.5m3.5 3.5a3.5 3.5 0 1 1-3.5 3.5m0 0A3.5 3.5 0 1 1 8.5 12");
}

</style>
