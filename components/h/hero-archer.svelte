<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y32ge8b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hero-archer" {...props}></Icon>
<style>
:global(.y32ge8b-d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm0 15.75l2.25-5l2.25 5m-2.25-5v-5.75m0 1.25H21.5M14 4a9.5 9.5 0 0 1 0 16m0-16l-6.5 8l6.5 8");
}

</style>
