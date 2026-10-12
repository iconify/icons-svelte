<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctvl36bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:charpai-sharp" {...props}></Icon>
<style>
:global(.ctvl36bls) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 6.5h14l-.45.89l-2.6 5.22l-.45.89h-15l.45-.89l2.6-5.22l.45-.89zm3.25 1.25l-2.25 4.5m7.25-4.5l-2.25 4.5m-7.5 1.25v6.75m10-6.75v6.75");
}

</style>
