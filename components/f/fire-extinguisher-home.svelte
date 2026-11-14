<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vadwfrb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-extinguisher-home" {...props}></Icon>
<style>
:global(.vadwfrb_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21v-9.5a3.25 3.25 0 0 1 6.5 0V21Zm3.25-12.75V6M7.5 5l7-1M13 6c3.5 0 5 1.5 5 4.5V14");
}

</style>
