<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq467ok5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monitor-curved" {...props}></Icon>
<style>
:global(.mq467ok5q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25q9.25-2.75 18.5 0v9.5Q12 12 2.75 14.75ZM12 13.5v6.75m-3.75 0h7.5");
}

</style>
