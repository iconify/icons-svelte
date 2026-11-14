<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ip9umh_bl"/><path class="hm6q_5uui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beetroot" {...props}></Icon>
<style>
:global(.hm6q_5uui) {
  d: path("M12 7.5c-4 0-6-2.25-5.5-4.25C10 3.25 12 5 12 7.5m0 0c4 0 6-2.25 5.5-4.25C14 3.25 12 5 12 7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ip9umh_bl) {
  d: path("M12 20.75C11 19 5.5 18.5 5.5 14a6.5 6.5 0 0 1 13 0c0 4.5-5.5 5-6.5 6.75");
}

</style>
