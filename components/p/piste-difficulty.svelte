<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cihsvz7ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:piste-difficulty" {...props}></Icon>
<style>
:global(.cihsvz7ao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m12.75-4h4a1.75 1.75 0 0 1 1.75 1.75v4A1.75 1.75 0 0 1 19.75 11h-4A1.75 1.75 0 0 1 14 9.25v-4a1.75 1.75 0 0 1 1.75-1.75m-2.513 10.237l2.026 2.026a1.75 1.75 0 0 1 0 2.474l-2.026 2.026a1.75 1.75 0 0 1-2.474 0l-2.026-2.026a1.75 1.75 0 0 1 0-2.474l2.026-2.026a1.75 1.75 0 0 1 2.474 0");
}

</style>
