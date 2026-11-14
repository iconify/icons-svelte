<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blx6omqfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:key-skeleton" {...props}></Icon>
<style>
:global(.blx6omqfc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7 0H21m-4.75 0v3.75h2.25V14H21v-2");
}

</style>
