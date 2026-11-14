<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kb-b5_0wk"/><path class="gcui2yj9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rear-window" {...props}></Icon>
<style>
:global(.gcui2yj9s) {
  d: path("M7.25 13.25a5.5 5.5 0 0 1 9.5 0M12 16h.01");
}

:global(.kb-b5_0wk) {
  d: path("M6.5 5h11L21 19H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
