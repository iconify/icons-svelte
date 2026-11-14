<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etat_gbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:civil-rights" {...props}></Icon>
<style>
:global(.etat_gbvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3.5 21.5V20c0-3.25 3-5.5 7.5-5.5c1.055 0 1.932.107 2.781.35M15.5 17h6m-6 3.5h6");
}

</style>
