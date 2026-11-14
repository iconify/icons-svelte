<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8l68rbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:core-network" {...props}></Icon>
<style>
:global(.k8l68rbei) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9h6v6H9ZM4.5 2.5a2 2 0 1 0 0 4a2 2 0 1 0 0-4Zm15 0a2 2 0 1 0 0 4a2 2 0 1 0 0-4Zm-15 15a2 2 0 1 0 0 4a2 2 0 1 0 0-4Zm15 0a2 2 0 1 0 0 4a2 2 0 1 0 0-4ZM6 6l3.5 3.5M18 6l-3.5 3.5M6 18l3.5-3.5M18 18l-3.5-3.5M9 12h6");
}

</style>
