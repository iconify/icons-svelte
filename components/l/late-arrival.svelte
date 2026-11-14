<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lk7oulbbp"/><path class="m-gmjhbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:late-arrival" {...props}></Icon>
<style>
:global(.lk7oulbbp) {
  d: path("M7.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.m-gmjhbdm) {
  d: path("M14.5 8v4l3 2m-15-5h2.25M2 12h2.75M2.5 15h2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
