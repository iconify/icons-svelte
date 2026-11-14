<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6b478nbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:audio-separation" {...props}></Icon>
<style>
:global(.d6b478nbv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5v3m4.25-4v5m4.25-6v7M16.25 4v4m4.25-3.5v3m-17 8v5m4.25-4v3m4.25-5v7m4.25-6v5m4.25-4v3");
}

</style>
