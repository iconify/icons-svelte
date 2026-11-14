<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bby_ajj6p"/><path class="zyas4xbks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hard-fork" {...props}></Icon>
<style>
:global(.bby_ajj6p) {
  d: path("M12 21v-9L5 5m7 7l7-7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zyas4xbks) {
  d: path("M5 9V5h4m6 0h4v4");
}

</style>
