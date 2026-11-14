<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_fnkk6yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:platform-bench" {...props}></Icon>
<style>
:global(.y_fnkk6yj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16V7H4Zm-1 7h18V14H3ZM6.5 7v3.5m0 3.5v5m11-12v3.5m0 3.5v5m-15 0h19");
}

</style>
