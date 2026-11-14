<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbx4nqbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cross-orthodox" {...props}></Icon>
<style>
:global(.sbx4nqbyl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m-2.5-16h5m-8 4h11m-9 5.5l7 3");
}

</style>
