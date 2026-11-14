<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru7a0r9ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:info-desk" {...props}></Icon>
<style>
:global(.ru7a0r9ae) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19m-17 0v6.5h15V15M7.25 7.25a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0M12 5.5h.01M12 8v2");
}

</style>
