<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1glweb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:acupuncture-needles" {...props}></Icon>
<style>
:global(.b1glweb4v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM17 7L6 18m-2.25 2.25h.01");
}

</style>
