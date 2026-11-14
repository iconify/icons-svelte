<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7d5qk_nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:padding" {...props}></Icon>
<style>
:global(.p7d5qk_nk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 3.5h4.75A6.125 6.125 0 0 1 20.5 9.625v4.75a6.125 6.125 0 0 1-6.125 6.125h-4.75A6.125 6.125 0 0 1 3.5 14.375v-4.75A6.125 6.125 0 0 1 9.625 3.5M8 8h.01M12 8h.01M16 8h.01M8 12h.01M16 12h.01M8 16h.01M12 16h.01M16 16h.01");
}

</style>
