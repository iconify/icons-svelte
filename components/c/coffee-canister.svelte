<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4vjwceux"/><path class="c6zdbzxqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coffee-canister" {...props}></Icon>
<style>
:global(.c6zdbzxqd) {
  d: path("M8.75 10.5h6.5v7h-6.5Z");
}

:global(.q4vjwceux) {
  d: path("M4.5 3h15v4h-15ZM6 7v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
