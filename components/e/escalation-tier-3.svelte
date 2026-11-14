<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwl3o3iiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:escalation-tier-3" {...props}></Icon>
<style>
:global(.xwl3o3iiw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 9.25l7.5-5.5l7.5 5.5m-15 5.5l7.5-5.5l7.5 5.5m-15 5.5l7.5-5.5l7.5 5.5");
}

</style>
