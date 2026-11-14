<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6sjs3r2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:compare" {...props}></Icon>
<style>
:global(.w6sjs3r2o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m-2.5-14H3m2.75-2.75L3 7.5l2.75 2.75m8.75 6.25H21m-2.75-2.75L21 16.5l-2.75 2.75");
}

</style>
