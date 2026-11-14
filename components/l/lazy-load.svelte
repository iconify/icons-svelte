<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyev_0jvj"/><path class="l76l-6b7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lazy-load" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l76l-6b7v) {
  d: path("m8 12.75l4 4l4-4");
}

:global(.tyev_0jvj) {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12m.75-3.75h.01m1.99-3h.01m2.99-2h.01M12 7v9.5");
}

</style>
