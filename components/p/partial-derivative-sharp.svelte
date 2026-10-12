<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kapzdccsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:partial-derivative-sharp" {...props}></Icon>
<style>
:global(.kapzdccsm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 5.5l2.1-1.75H12c3.25 0 5.5 2.75 5.5 7.5c0 5.75-2.75 9-6.25 9c-2.75 0-4.75-2-4.75-4.5s2-4.5 4.75-4.5c2.25 0 4.25 1.25 5.75 3.5");
}

</style>
