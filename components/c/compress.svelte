<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu_41wbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:compress" {...props}></Icon>
<style>
:global(.yu_41wbrt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12h16m-8-9v5.5m-3-3l3 3l3-3M12 21v-5.5m-3 3l3-3l3 3");
}

</style>
