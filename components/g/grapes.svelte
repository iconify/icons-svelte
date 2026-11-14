<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6actfflk"/><path class="l0gd08sdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grapes" {...props}></Icon>
<style>
:global(.c6actfflk) {
  d: path("M5.5 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm7 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.l0gd08sdg) {
  d: path("M9 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.25 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 3v3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
