<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o9ce6l_oh"/><path class="mgxqogbjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cause-domestic-abuse" {...props}></Icon>
<style>
:global(.mgxqogbjf) {
  d: path("M8 20.5V15h3.5v5.5m3.5 1.25l4.5-4.5a2.25 2.25 0 1 0-3 0l4.5 4.5");
}

:global(.o9ce6l_oh) {
  d: path("M12.344 20.5H3.5v-10L12 3.25l8.5 7.25v.656");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
