<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9rwsw31k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-diagonal-mouth" {...props}></Icon>
<style>
:global(.f9rwsw31k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m6.25-2.5h.01m6.49 0h.01M10 17l6.5-3.5");
}

</style>
