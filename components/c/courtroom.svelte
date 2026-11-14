<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjr5f8bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:courtroom" {...props}></Icon>
<style>
:global(.wjr5f8bym) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 4.964L17.536 8.5a2.5 2.5 0 0 1 0 3.536a2.5 2.5 0 0 1-3.536 0L10.464 8.5a2.5 2.5 0 0 1 0-3.536a2.5 2.5 0 0 1 3.536 0m-1.75 5.286L4 18.5m10-1h5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
