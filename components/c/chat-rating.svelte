<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_70p3bcx"/><path class="np9hy9bcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chat-rating" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_70p3bcx) {
  d: path("M5 3h14a2.5 2.5 0 0 1 2.5 2.5V14a2.5 2.5 0 0 1-2.5 2.5h-9l-4 4v-4H5A2.5 2.5 0 0 1 2.5 14V5.5A2.5 2.5 0 0 1 5 3");
}

:global(.np9hy9bcx) {
  d: path("m12.5 7l.159.396a1.5 1.5 0 0 0 1.257.937l.511.047a.569.569 0 0 1 .323.995l-.36.315a1.5 1.5 0 0 0-.488 1.397l.106.583a.574.574 0 0 1-.883.58l-.293-.195a1.5 1.5 0 0 0-1.664 0l-.293.195a.574.574 0 0 1-.883-.58l.106-.583A1.5 1.5 0 0 0 9.61 9.69l-.36-.315a.569.569 0 0 1 .323-.995l.511-.047a1.5 1.5 0 0 0 1.257-.937L11.5 7a.539.539 0 0 1 1 0");
}

</style>
