<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s_-mj0rqn"/><path class="wm948pixd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:door-handle-pull" {...props}></Icon>
<style>
:global(.s_-mj0rqn) {
  d: path("M6 21.5v-17a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v17m-14.5 0h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wm948pixd) {
  d: path("M13 7.5h1.75v9H13");
}

</style>
