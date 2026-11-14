<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8c6huevd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:incorporation" {...props}></Icon>
<style>
:global(.d8c6huevd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 20.5H3V9h4.5V2.5h9v9.7m-6-5.7h.01m2.99 0h.01m-3.01 4h.01m2.99 0h.01M18 15v6m-3-3h6");
}

</style>
