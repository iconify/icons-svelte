<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gc2fxkbqd"/><path class="nm0apdcex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flower-bud" {...props}></Icon>
<style>
:global(.gc2fxkbqd) {
  d: path("M12 2.5c2 2.5 4.5 5 4.5 7.5a4.5 4.5 0 0 1-9 0c0-2.5 2.5-5 4.5-7.5Zm0 15v4");
}

:global(.nm0apdcex) {
  d: path("M12 17.5c-2.5 0-3.75-2.5-3.75-5m3.75 5c2.5 0 3.75-2.5 3.75-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
