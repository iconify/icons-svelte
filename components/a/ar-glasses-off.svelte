<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c31lf0mig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ar-glasses-off" {...props}></Icon>
<style>
:global(.c31lf0mig) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.4V16h-8V8h1.6m9.4 1.6V8h8v8h-1.6M2.5 10.5v-4m19 4v-4m-17-2L20 20");
}

</style>
