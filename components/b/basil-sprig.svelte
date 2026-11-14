<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xcjakk9aa"/><path class="pdmg9_kfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:basil-sprig" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pdmg9_kfz) {
  d: path("M12 9c-2-1.5-2-4 0-5.5c2 1.5 2 4 0 5.5");
}

:global(.xcjakk9aa) {
  d: path("M12 21V9m0 5c-3.5 0-6-2-6-5.5c3.5 0 6 2 6 5.5m0-2c3.5 0 6-2 6-5.5c-3.5 0-6 2-6 5.5");
}

</style>
