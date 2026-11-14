<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvms5obab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:brewery-tanks" {...props}></Icon>
<style>
:global(.qvms5obab) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16V8a3.5 3.5 0 0 1 7 0v8Zm1.5 0v4.5m4-4.5v4.5M14 16V8a3.5 3.5 0 0 1 7 0v8Zm1.5 0v4.5m4-4.5v4.5M10 12h4M3 8h7m4 0h7");
}

</style>
