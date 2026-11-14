<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uxdy0cbia"/><path class="ruql7rrrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:effervescent-tablet" {...props}></Icon>
<style>
:global(.ruql7rrrq) {
  d: path("M8.5 17.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uxdy0cbia) {
  d: path("m3.5 9.5l1.5 12h10l1.5-12M4 13h12m.35-9.303l4.532-2.113l1.268 2.719l-4.532 2.113Z");
}

</style>
