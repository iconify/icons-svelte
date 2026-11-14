<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rs6uchb6o"/><path class="z9ywplblf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:log-stack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rs6uchb6o) {
  d: path("M4 15.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.z9ywplblf) {
  d: path("M8 8.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m0 7h.01m7.99 0h.01M12 8.5h.01");
}

</style>
