<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uafg_qxau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:catamaran-sail" {...props}></Icon>
<style>
:global(.uafg_qxau) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.5v-14l6.5 11H12m-9 3h18m-17.5 0V18A2.25 2.25 0 0 0 8 18v-1.5m8 0V18a2.25 2.25 0 0 0 4.5 0v-1.5");
}

</style>
