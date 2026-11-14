<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ikc8mlwrt"/><path class="mg5xadb2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:forum-post" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikc8mlwrt) {
  d: path("M4.5 7h10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-6L5 21v-3h-.5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2");
}

:global(.mg5xadb2e) {
  d: path("M8.5 7V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-3M6 11h7m-7 3.5h4.5");
}

</style>
