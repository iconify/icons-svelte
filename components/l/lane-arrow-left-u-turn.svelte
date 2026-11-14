<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cjhbo82aw"/><path class="wkjl5qelv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lane-arrow-left-u-turn" {...props}></Icon>
<style>
:global(.cjhbo82aw) {
  d: path("M18 21V8.5a4.25 4.25 0 0 0-8.5 0v7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wkjl5qelv) {
  d: path("m6 12l3.5 3.5L13 12");
}

</style>
