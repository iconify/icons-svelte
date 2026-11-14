<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h75uamgzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beaker-measure" {...props}></Icon>
<style>
:global(.h75uamgzm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5v6l-6 11c-.5 1 0 2 1.25 2h14.5c1.25 0 1.75-1 1.25-2l-6-11v-6M8 2.5h8M6 15h12M7.75 12H10m-5.25 6h2.5");
}

</style>
