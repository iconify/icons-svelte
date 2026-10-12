<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laf5i3bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rebar" {...props}></Icon>
<style>
:global(.laf5i3bdn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 15.75l13-13M5.5 18.5l13-13M8.25 21.25l13-13M11.5 5.5l7 7m-13-1l7 7");
}

</style>
