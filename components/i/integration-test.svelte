<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj6nzpbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:integration-test" {...props}></Icon>
<style>
:global(.aj6nzpbaw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H12V10H2.5ZM12 19.2v2.3H2.5V14H12v2.8M7.25 10v4m7.5 4l2 2L21 15.75");
}

</style>
