<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7-8vceby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bmi-gauge" {...props}></Icon>
<style>
:global(.p7-8vceby) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17a9.5 9.5 0 0 1 19 0Zm4.75-8.25l1.5 2.5m8-2.5l-1.5 2.5M12 17l.75-6.5M12 17h.01");
}

</style>
