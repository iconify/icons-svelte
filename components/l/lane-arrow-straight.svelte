<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p00pk_bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lane-arrow-straight" {...props}></Icon>
<style>
:global(.p00pk_bvl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V2.75m-6.5 6.5l6.5-6.5l6.5 6.5");
}

</style>
